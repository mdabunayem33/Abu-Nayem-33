<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LeetCode Stats for GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        
        .leetcode-container {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 20px;
            width: 100%;
            max-width: 350px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        
        .header {
            text-align: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid #30363d;
        }
        
        .header h1 {
            font-size: 24px;
            color: #58a6ff;
            margin-bottom: 5px;
        }
        
        .username {
            color: #8b949e;
            font-size: 16px;
        }
        
        .difficulty {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
        }
        
        .diff-item {
            text-align: center;
            flex: 1;
            padding: 10px;
        }
        
        .diff-item:not(:last-child) {
            border-right: 1px solid #30363d;
        }
        
        .diff-title {
            font-size: 14px;
            margin-bottom: 5px;
            color: #8b949e;
        }
        
        .easy {
            color: #3fb950;
        }
        
        .medium {
            color: #d29922;
        }
        
        .hard {
            color: #db6d28;
        }
        
        .count {
            font-size: 20px;
            font-weight: bold;
        }
        
        .progress-container {
            margin-top: 20px;
        }
        
        .progress-title {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
            font-size: 14px;
        }
        
        .progress-bar {
            height: 8px;
            background-color: #21262d;
            border-radius: 4px;
            overflow: hidden;
            margin-bottom: 15px;
        }
        
        .progress-fill {
            height: 100%;
            border-radius: 4px;
        }
        
        .progress-fill.easy {
            background-color: #3fb950;
            width: 45%;
        }
        
        .progress-fill.medium {
            background-color: #d29922;
            width: 20%;
        }
        
        .progress-fill.hard {
            background-color: #db6d28;
            width: 10%;
        }
        
        .profile-info {
            margin-top: 25px;
            padding-top: 15px;
            border-top: 1px solid #30363d;
        }
        
        .profile-header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .profile-name {
            font-size: 18px;
            font-weight: bold;
            margin-right: 10px;
        }
        
        .profile-rating {
            background-color: #21262d;
            color: #8b949e;
            padding: 2px 8px;
            border-radius: 12px;
            font-size: 12px;
        }
        
        .profile-stats {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }
        
        .stat-item {
            font-size: 14px;
        }
        
        .stat-label {
            color: #8b949e;
        }
        
        .stat-value {
            font-weight: bold;
        }
        
        @media (max-width: 400px) {
            .leetcode-container {
                padding: 15px;
            }
            
            .diff-item {
                padding: 8px 5px;
            }
            
            .count {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
    <div class="leetcode-container">
        <div class="header">
            <h1>Leetcode</h1>
            <div class="username">mahia12</div>
        </div>
        
        <div class="difficulty">
            <div class="diff-item">
                <div class="diff-title easy">Easy</div>
                <div class="count easy">4/892</div>
            </div>
            <div class="diff-item">
                <div class="diff-title medium">Medium</div>
                <div class="count medium">2/1907</div>
            </div>
            <div class="diff-item">
                <div class="diff-title hard">Hard</div>
                <div class="count hard">0/863</div>
            </div>
        </div>
        
        <div class="progress-container">
            <div class="progress-title">
                <span>Solved</span>
                <span>6/3662</span>
            </div>
            <div class="progress-bar">
                <div class="progress-fill easy"></div>
            </div>
        </div>
        
        <div class="profile-info">
            <div class="profile-header">
                <div class="profile-name">Mahia Momo</div>
                <div class="profile-rating">Unrated</div>
            </div>
            
            <div class="profile-stats">
                <div class="stat-item">
                    <span class="stat-label">Contest Rating:</span>
                    <span class="stat-value">0</span>
                </div>
                <div class="stat-item">
                    <span class="stat-label">Max Rating:</span>
                    <span class="stat-value">0</span>
                </div>
                <div class="stat-item">
                    <span class="stat-label">Rated Contests:</span>
                    <span class="stat-value">0</span>
                </div>
                <div class="stat-item">
                    <span class="stat-label">Problems Solved:</span>
                    <span class="stat-value">1</span>
                </div>
                <div class="stat-item">
                    <span class="stat-label">Submissions:</span>
                    <span class="stat-value">1</span>
                </div>
                <div class="stat-item">
                    <span class="stat-label">Friend of:</span>
                    <span class="stat-value">5</span>
                </div>
                <div class="stat-item">
                    <span class="stat-label">Contribution:</span>
                    <span class="stat-value">0</span>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
