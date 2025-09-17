<!DOCTYPE html>
<html lang="zh-CN">
<body>
    <input type="file" id="fileInput">
    <img id="previewImg" alt="预览图片">
    <script>
        const fileInput = document.getElementById('fileInput');
        const previewImg = document.getElementById('previewImg');
        fileInput.addEventListener('change', function (e) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function (evt) {
                    previewImg.src = evt.target.result;
                    previewImg.style.display = 'block';
                };
                reader.readAsDataURL(file);
            }
        });
    </script>
</body>
</html>
