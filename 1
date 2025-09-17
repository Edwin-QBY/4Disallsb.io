<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>照片上传工具</title>
    <style>
        /* 基础样式，适配手机 */
        body {
            font-family: Arial, sans-serif;
            max-width: 600px;
            margin: 20px auto;
            padding: 0 15px;
            text-align: center;
        }
        .upload-container {
            margin-top: 30px;
        }
        /* 上传按钮样式 */
        #file-upload {
            display: none; /* 隐藏原生按钮 */
        }
        .upload-btn {
            padding: 12px 25px;
            background-color: #2196F3;
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
        }
        .upload-btn:hover {
            background-color: #1976D2;
        }
        /* 预览图样式 */
        #preview-img {
            margin-top: 25px;
            max-width: 100%;
            max-height: 400px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            display: none; /* 初始隐藏，上传后显示 */
        }
        .tip {
            margin-top: 15px;
            color: #666;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <h2>上传你的照片</h2>
    <div class="upload-container">
        <!-- 自定义上传按钮 -->
        <label for="file-upload" class="upload-btn">选择本地照片</label>
        <!-- 原生文件选择控件 -->
        <input type="file" id="file-upload" accept="image/*">
        <!-- 照片预览区域 -->
        <img id="preview-img" alt="照片预览">
        <p class="tip">支持JPG、PNG、WEBP等常见图片格式</p>
    </div>

    <script>
        // 获取元素
        const fileInput = document.getElementById('file-upload');
        const previewImg = document.getElementById('preview-img');

        // 监听文件选择事件
        fileInput.addEventListener('change', function(e) {
            // 获取选中的文件
            const file = e.target.files[0];
            if (file) {
                // 检查是否为图片类型
                if (file.type.startsWith('image/')) {
                    // 创建文件读取对象
                    const reader = new FileReader();
                    // 读取文件完成后显示预览
                    reader.onload = function(event) {
                        previewImg.src = event.target.result;
                        previewImg.style.display = 'block'; // 显示预览图
                    }
                    // 以DataURL格式读取文件
                    reader.readAsDataURL(file);
                } else {
                    alert('请选择图片文件！');
                    fileInput.value = ''; // 清空选择
                }
            }
        });
    </script>
</body>
</html>
