<p align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/4e77ba0d-f5bb-4fb9-ab5d-dfd96fcb89f0" style="width:63%;" />
</p>

<br>

# 政法智言大模型v1.0（Lexipolis-9B-Chat）

## 模型简介

**政法智言大模型v1.0** **(_Lexipolis-9B-Chat_)** 由清华大学THUDM开源的`GLM-4-9B-Chat`微调得到。

采用LoRA算法进行微调：微调过程包括增量预训练与指令微调，其中增量训练使用的数据集包含涉政新闻、工作汇报、国家法律法规条文、领导人讲话语录、政法课程教材、公文、国家部门章程，数据量约1GB。

指令微调使用的数据包含案件审判（案件事实与审判结果对齐）、法条引用（案件事实与法条引用对齐）、指令理解语料（撰写“涉政新闻”的指令与涉政新闻内容对齐等），数据量约550MB。

## 模型地址

**Huggingface:** https://huggingface.co/Duyu/Lexipolis-9B-Chat

## 项目团队人员

齐鲁工业大学（山东省科学院）计算机科学与技术学部 杜宇（202103180009@stu.qlu.edu.cn）

----

# Lexipolis v1.0

## Lexipolis-9B-Chat (v1.0) Model Overview

**Lexipolis-9B-Chat** version 1.0 is fine-tuned from Tsinghua University's THUDM's `GLM-4-9B-Chat`.

It employs the LoRA algorithm for fine-tuning, which includes incremental pre-training and instruction tuning. The incremental training uses a dataset comprising political news, work reports, national laws and regulations, speeches from leaders, political and legal textbooks, official documents, and regulations from national departments, with a data volume of about 1GB.

The instruction tuning uses data that includes case trials (aligning case facts with trial results), legal citation (aligning case facts with legal citations), and instruction understanding corpus (aligning instructions for writing "political news" with the content of the news, etc.), with a data volume of about 550MB.

## Website of Lexipolis LLM

**Huggingface:** https://huggingface.co/Duyu/Lexipolis

## Project Team

Faculty of Computer Science and Technology, Qilu University of Technology (Shandong Academy of Sciences) 
Du Yu (202103180009@stu.qlu.edu.cn)

-----

## Visitor Statistics

<div><b>Number of Total Visits (All of Duyu09's GitHub Projects): </b><br><img src="https://profile-counter.glitch.me/duyu09/count.svg" /></div> 

<div><b>Number of Total Visits (Lexipolis LLM): </b>
<br><img src="https://profile-counter.glitch.me/duyu09-Lexipolis-v1/count.svg" /></div> 
