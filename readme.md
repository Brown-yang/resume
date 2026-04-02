\documentclass[11pt,a4paper]{article}
\usepackage[UTF8,fontset=none]{ctex}
\usepackage{geometry}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{xcolor}
\usepackage{graphicx}
\usepackage{titlesec}

\setCJKmainfont{Noto Sans CJK SC}
\setCJKsansfont{Noto Sans CJK SC}
\setCJKmonofont{Noto Sans Mono CJK SC}

\geometry{left=1.5cm,right=1.5cm,top=1cm,bottom=1cm}
\pagestyle{empty}
\setlist[itemize]{leftmargin=*,nosep,topsep=0pt,itemsep=1pt}
\setlength{\parindent}{0pt}
\setlength{\parskip}{2pt}
\linespread{0.96}
\titleformat{\section}{\normalsize\bfseries}{}{0pt}{}
\titlespacing*{\section}{0pt}{4pt}{2pt}

\definecolor{linkcolor}{RGB}{0,0,139}
\hypersetup{colorlinks=true,urlcolor=linkcolor}

\begin{document}

\begin{minipage}[t]{0.75\textwidth}
\vspace{0pt}
{\LARGE \textbf{王洋}}\\[3pt]
男 $\mid$ 26岁 $\mid$ 15623362892 $\mid$ 1439256987@qq.com\\[2pt]
算法工程师 $\mid$ 期望薪资：20-40K $\mid$ 期望城市：深圳
\end{minipage}
\hfill
\begin{minipage}[t]{0.2\textwidth}
\vspace{0pt}
\raggedleft
\includegraphics[width=1.6cm]{fig.jpg}
\end{minipage}

\vspace{1pt}
\noindent\rule{\textwidth}{0.4pt}

\section*{个人优势}
\vspace{-4pt}
四级534，六级483；发表TAI、TNSM、ISPA等多篇期刊会议论文；湖南科技大学2023、2024年国家奖学金；小红书技术博主，粉丝1000+，零豹AI工作室创始人，带领团队从0到1打造具身智能技术方案

\section*{教育经历}
\vspace{-4pt}
\textbf{合肥工业大学} \hfill 2025 -- 2029\\
博士 $\mid$ 电子信息

\textbf{湖南科技大学} \hfill 2022 -- 2025\\
硕士 $\mid$ 计算机科学与技术

\textbf{湖北工业大学} \hfill 2018 -- 2022\\
本科 $\mid$ 软件工程

\section*{实习经历}
\vspace{-4pt}
\textbf{方心科技股份有限公司} \hfill HPC算法 \hfill 2024.09 -- 2024.12\\
\textbf{特征匹配算法部署与加速}
完成XFeat+LightGlue与SuperPoint+LightGlue在Jetson Orin上的部署与加速，包含ONNX/TensorRT转换、模型切割与组装。实现算法推理显著提速（XFeat+LightGlue 1.702s→0.0343s，SuperPoint+LightGlue 0.28s→0.08s），熟悉ARM架构开发、CUDA并行计算及CMake。


\textbf{深圳华大基因科技有限公司} \hfill NLP算法 \hfill 2024.06 -- 2024.09\\
\textbf{武大生命科学研究}
参与武汉能所与研究院联合项目，研究方向涵盖辅助生殖、医学文本特征提取及多组学基因研究。负责文献调研并将前沿方法应用于辅助生殖领域，协助撰写项目申请书。复现相关论文算法，完成基因数据预处理、特征选择（SCFS）及患者聚类（SNF+谱聚类），熟悉LangChain大模型框架，整理一体机项目代码逻辑。


\section*{项目经历}
\vspace{-4pt}
\textbf{VLA模型训练微调部署} \hfill 负责人 \hfill 2025.02 -- 2025.11

负责VLA模型训练、微调及多平台部署，涵盖Pi0、Pi0.5、GR00T、ACT等模型，在Franka、UR、Aubo、G1等多款真机上落地应用。全流程参与数据采集与格式转换、模型微调、控制代码开发，实现异步推理与RTC推理，完成机器人端实时控制与多平台适配。

\textbf{通用机器人数据采集开发} \hfill 研发 \hfill 2024.04 -- 2025.02

开发利用VR实现机器人和机械臂控制系统。将机械臂末端和人的手腕进行绑定，实现VR中手的坐标位置和机械臂坐标对齐转换。利用机器人urdf文件对获取坐标进行IK解算，将解算角度实时发布到机器人进行控制，实现利用一个VR控制多种异构机器人进行数据采集，掌握ROS、机械臂运动学、Kinect等技术。



\section*{资格证书}
\vspace{-4pt}
CET-6 $\mid$ CET-4 $\mid$ CCF CSP认证

\end{document}
