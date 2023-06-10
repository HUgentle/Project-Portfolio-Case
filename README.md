# Project-Portfolio-Case

Pn：项目组合中子项目数量；

Net_PP：子项目之间的约束关系，当Net_PP(i,j)=1时，项目j必须在项目i完成后才可开始；

Net_P：子项目中技能之间的约束关系，当Net_P{i}(s,m)=1时，项目i中的技能m必须在技能s完成后才可开始；

Proj_Skill：子项目中活动所需技能，当Proj_Skill(i,s)=1时，项目i需要技能s；

Work_Content：子项目中技能持续时间，当执行技能s的资源技能熟练度为1时，子项目i中技能s持续时间为Work_Content(i,s)；

Res_Skill：资源的技能熟练度，资源k对技能s的熟练度为Res_Skill(k,s)；

Res_Out_rate：资源在每时刻的中断概率，资源k的中断概率为Res_Out_rate(k)；

Res_Cost：资源的单位时间使用成本，资源k的单位时间使用成本为Res_Cost(k)；

Weight_of_strategy：项目中各个技能的战略收益。
