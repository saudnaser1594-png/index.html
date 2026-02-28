<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechTask | Dashboard</title>
    <style>
        :root {
            --primary: #2c3e50;
            --accent: #27ae60;
            --bg: #f4f7f6;
        }
        body { font-family: 'Segoe UI', Tahoma, sans-serif; background-color: var(--bg); margin: 0; color: #333; }
        
        /* Header */
        header { background: var(--primary); color: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        
        /* Main Layout */
        .container { max-width: 1000px; margin: 2rem auto; padding: 0 1rem; }
        
        /* Task Input Area */
        .task-input { background: white; padding: 1.5rem; border-radius: 10px; display: flex; gap: 10px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); margin-bottom: 2rem; }
        input { flex: 1; padding: 12px; border: 1px solid #ddd; border-radius: 5px; outline: none; }
        button { background: var(--accent); color: white; border: none; padding: 10px 25px; border-radius: 5px; cursor: pointer; font-weight: bold; transition: 0.3s; }
        button:hover { background: #219150; }

        /* Task List */
        .task-list { display: grid; gap: 15px; }
        .task-item { background: white; padding: 1rem; border-radius: 8px; display: flex; justify-content: space-between; align-items: center; border-right: 5px solid var(--accent); box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        
        .delete-btn { background: #e74c3c; padding: 5px 10px; font-size: 0.8rem; }
    </style>
</head>
<body>

<header>
    <h2>TechTask Enterprise</h2>
    <span>مرحباً، سعود الدهام</span>
</header>

<div class="container">
    <div class="task-input">
        <input type="text" placeholder="اكتب مهمة جديدة هنا...">
        <button>إضافة مهمة</button>
    </div>

    <div class="task-list">
        <div class="task-item">
            <div>
                <strong>تصميم واجهة المستخدم</strong>
                <p style="margin: 5px 0 0; font-size: 0.8rem; color: #666;">الحالة: قيد التنفيذ</p>
            </div>
            <button class="delete-btn">حذف</button>
        </div>
    </div>
</div>

</body>
</html>
