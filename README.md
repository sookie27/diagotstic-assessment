<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>焦虑抑郁自评（SAS及SDS）测评</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>焦虑抑郁自评（SAS及SDS）测评</h1>
        
        <!-- 测试人信息输入 -->
        <div id="info-section" class="section active">
            <h2>基本信息</h2>
            <div class="form-group">
                <label for="name">测试人名称：</label>
                <input type="text" id="name" placeholder="请输入您的姓名" required>
            </div>
            <button id="start-btn" class="btn">开始测评</button>
        </div>
        
        <!-- SAS焦虑测评 -->
        <div id="sas-section" class="section">
            <h2>焦虑自评量表（SAS）</h2>
            <p class="instruction">请根据您最近一周的实际感受，选择最符合您情况的答案：</p>
            <div id="sas-questions" class="questions"></div>
            <div class="nav-buttons">
                <button id="sas-prev-btn" class="btn btn-secondary">上一步</button>
                <button id="sas-next-btn" class="btn">下一步</button>
            </div>
        </div>
        
        <!-- SDS抑郁测评 -->
        <div id="sds-section" class="section">
            <h2>抑郁自评量表（SDS）</h2>
            <p class="instruction">请根据您最近一周的实际感受，选择最符合您情况的答案：</p>
            <div id="sds-questions" class="questions"></div>
            <div class="nav-buttons">
                <button id="sds-prev-btn" class="btn btn-secondary">上一步</button>
                <button id="sds-next-btn" class="btn">提交测评</button>
            </div>
        </div>
        
        <!-- 测评结果 -->
        <div id="result-section" class="section">
            <h2>测评结果</h2>
            <div id="result-content" class="result"></div>
            <button id="restart-btn" class="btn">重新测评</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
