# contract-plex

基于 AI 的自动化合约管理与解析工具。

## 安装

确保已安装 Python 3.8+，使用以下命令安装依赖：

```bash
pip install -r requirements.txt
```

## 使用方法

通过 `contractplex.py` 对合约文档进行自动化分析：

```python
from contractplex import ContractAnalyzer

analyzer = ContractAnalyzer(api_key="your_key")
result = analyzer.analyze("contract.pdf")
print(result)
```

## 测试

运行内置测试脚本以验证核心功能：

```bash
python test_contractplex.py
```

## 许可证

本项目采用 MIT 许可证。详见 LICENSE 文件。

