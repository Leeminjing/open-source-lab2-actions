# GitHub Actions 自动化测试实验

本项目包含加法、乘法函数与 pytest 单元测试。每次 push、pull_request 或手动触发时，GitHub Actions 自动安装依赖并执行测试。

```sh
python -m pip install -r requirements.txt
python -m pytest -v
```

实验过程：先验证正确实现通过；再将 add 错改为乘法，观察断言失败；最后修复并确认最新工作流成功。失败提交仅用于教学实验。
