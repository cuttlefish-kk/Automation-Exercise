Automation UI Testing Project
Selenium + Python + Pytest 电商与 Web 组件 UI 自动化测试

📌 项目简介
该项目基于 AutomationExercise（电商站点） 与 DemoQA（组件站点）
构建 UI 自动化测试体系，覆盖电商 E2E 流程和常见前端组件。

🏗 技术栈

Python 3.x
Selenium WebDriver
Pytest
Webdriver-Manager
Pytest-HTML 报告
Requests（辅助登录/接口验证）

🛒 自动化覆盖范围
AutomationExercise（电商站点）
添加商品到购物车
购物车数量校验
跳转 Checkout（含弹窗登录处理）
登录 / 注册流程（成功 + 失败校验）
填写订单信息
提交订单并验证 ORDER PLACED
截图与 HTML 报告生成
DemoQA（组件站点）
表单填写与提交
iframe 操作
Alert 弹窗
Checkbox / Radio
Select 下拉框
动态元素显式等待

📁 目录结构
project/
│── tests/
│    ├── test_checkout_flow.py
│    ├── test_demoqa_form.py
│── pages/
│    ├── login_page.py
│    ├── cart_page.py
│── utils/
│    ├── helpers.py
│── screenshots/
│── pytest.ini
│── requirements.txt
│── README.md

🧪 运行测试
pytest -v --html=report.html --self-contained-html
📷 测试报告（带截图）
report.html 自动生成
失败自动截图

⭐ 项目亮点
动态等待、iframe、alert、遮挡处理
E2E 流程自动化
Page Object 模式封装
自动截图 + HTML 报告
代码结构清晰，可复用性高
