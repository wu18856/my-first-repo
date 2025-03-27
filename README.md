# my-first-repo
my first repo in learning how to use github to create my new repo
there is no signifucant information in this file, but it is also very important to me, because it is the first time that i try to use the github to strenthen my learning.
go on. and go on.


# 第一堂生物信息学课程笔记

## 算法（Algorithm） vs 模型（Model）

### 定义
- **算法**  
  一系列解决问题的明确步骤（如排序、搜索）。  
  示例：  
  ```python
  def quick_sort(arr):
      if len(arr) <= 1:
          return arr
      pivot = arr[len(arr)//2]
      left = [x for x in arr if x < pivot]
      middle = [x for x in arr if x == pivot]
      right = [x for x in arr if x > pivot]
      return quick_sort(left) + middle + quick_sort(right)

- **模型** 
对数据关系的数学抽象，用于预测或解释现象。
示例：线性回归模型

**公式代码**\
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

核心区别
特性	算法	模型
目标	解决具体问题	描述数据关系
形式	步骤流程	数学表达式
输出	结果（如排序列表）	预测值或概率分布



#### **2. 本学期学习计划**

## 生物信息学学习计划

### 目标
- 掌握基因组序列分析基础（BLAST、多序列比对）
- 熟练使用 Python/R 处理生物数据
- 完成蛋白质结构预测的课程项目

### 时间安排
- **第一阶段（1-4周）**  
   - [x] 学习基础 Linux 命令与 Shell 脚本  
   - [ ] 完成《生物信息学算法导论》第1-3章  
   - 关键工具：  
     - `Biopython`：用于序列分析  
     - `SAMtools`：处理测序数据  

- **第二阶段（5-8周）**  
   - 实践项目：  
     - 使用 `Bowtie2` 进行 RNA-seq 数据比对  
     - 在 GitHub 仓库中记录代码与结果:cite[8]

- **第三阶段（9-12周）**  
   - 小组合作完成蛋白质折叠预测（工具：`AlphaFold`）  
   - 撰写项目报告，包含：  
     - 方法流程图（示例）：  
       ```mermaid
       graph LR
           A[原始数据] --> B(预处理)
           B --> C{质量评估}
           C -->|合格| D[建模]
           C -->|不合格| E[重新采样]
       ```
