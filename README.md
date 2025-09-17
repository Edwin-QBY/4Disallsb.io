<!DOCTYPE html>
<html lang="zh-CN">
<body>
    <input type="file" id="fileInput">
    <img src="https://ani.hinson.azz.io/Image/20250917-0cefb23e-IMG 0469.jpeg" alt="作業照片- 2025年09月17日*>
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
