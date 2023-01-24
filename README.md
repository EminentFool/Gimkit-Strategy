# Gimkit Strategy Calculator #

EminentFool: I have updated the script to work reasonably well with current gimkit rules. Unfortunately I do not know python at all, and this was the best I could do. The money calculations are a bit off, as are the calculations for powerup prices. Furthermore, I was unable to add the quadgrader powerup, as-once again- I do not actually know any python. I will likely come back to fix it more after I learn a little about python.


Note: The below strategy is unfortunately outdated for the current Gimkit game. Feel free to play around with the code and update it according to current Gimkit rules.

`calc-gimkit-strategy.py` is a Python script by [Noble H. Mushtak](https://noblemushtak.pythonanywhere.com/) which generates optimal strategies for the educational game [Gimkit](https://www.gimkit.com/). For example, here is the optimal strategy for going from $1 to over $4,000,000,000 and buying all Level 10 Gimkit upgrades except insurance in as few steps as possible (all steps which are not just answering a normal question are in bold):


updated strategy is as follows:

Number of Steps: 221
1. Answer 1 question, bringing your total up to $2
2. Answer 1 question, bringing your total up to $4
3. Answer 1 question, bringing your total up to $6
4. Answer 1 question, bringing your total up to $8
5. Answer 1 question, bringing your total up to $10
6. Buy the Level 2 ($5) money per question upgrade for $10, making your total $0
7. Answer 1 question, bringing your total up to $6
8. Answer 1 question, bringing your total up to $12
9. Answer 1 question, bringing your total up to $18
10. Answer 1 question, bringing your total up to $24
11. Buy the Level 2 ($3) streak bonus upgrade for $20, making your total $4
12. Answer 1 question, bringing your total up to $12
13. Answer 1 question, bringing your total up to $20
14. Answer 1 question, bringing your total up to $28
15. Answer 1 question, bringing your total up to $36
16. Answer 1 question, bringing your total up to $44
17. Answer 1 question, bringing your total up to $52
18. Answer 1 question, bringing your total up to $60
19. Answer 1 question, bringing your total up to $68
20. Answer 1 question, bringing your total up to $76
21. Answer 1 question, bringing your total up to $84
22. Answer 1 question, bringing your total up to $92
23. Answer 1 question, bringing your total up to $100
24. Buy the Level 3 ($50) money per question upgrade for $100, making your total $0
25. Answer 1 question, bringing your total up to $53
26. Buy the Level 2 (1.5x) multiplier upgrade for $50, making your total $3
27. Answer 1 question, bringing your total up to $83
28. Answer 1 question, bringing your total up to $163
29. Answer 1 question, bringing your total up to $243
30. Answer 1 question, bringing your total up to $323
31. Buy the Level 3 (2x) multiplier upgrade for $300, making your total $23
32. Answer 1 question, bringing your total up to $129
33. Answer 1 question, bringing your total up to $235
34. Answer 1 question, bringing your total up to $341
35. Buy and use the discounter for $305, making your total $36
36. Answer 1 question, bringing your total up to $142
37. Answer 1 question, bringing your total up to $248
38. Answer 1 question, bringing your total up to $354
39. Answer 1 question, bringing your total up to $460
40. Answer 1 question, bringing your total up to $566
41. Answer 1 question, bringing your total up to $672
42. Answer 1 question, bringing your total up to $778
43. Buy the Level 4 ($100) money per question upgrade for $750, making your total $28
44. Answer 1 question, bringing your total up to $234
45. Answer 1 question, bringing your total up to $440
46. Answer 1 question, bringing your total up to $646
47. Answer 1 question, bringing your total up to $852
48. Answer 1 question, bringing your total up to $1058
49. Answer 1 question, bringing your total up to $1264
50. Answer 1 question, bringing your total up to $1470
51. Answer 1 question, bringing your total up to $1676
52. Buy the Level 4 (3x) multiplier upgrade for $1500, making your total $176
53. Answer 1 question, bringing your total up to $485
54. Answer 1 question, bringing your total up to $794
55. Answer 1 question, bringing your total up to $1103
56. Answer 1 question, bringing your total up to $1412
57. Answer 1 question, bringing your total up to $1721
58. Buy the Level 4 ($50) streak bonus upgrade for $1500, making your total $221
59. Answer 1 question, bringing your total up to $671
60. Answer 1 question, bringing your total up to $1121
61. Answer 1 question, bringing your total up to $1571
62. Answer 1 question, bringing your total up to $2021
63. Answer 1 question, bringing your total up to $2471
64. Answer 1 question, bringing your total up to $2921
65. Answer 1 question, bringing your total up to $3371
66. Answer 1 question, bringing your total up to $3821
67. Answer 1 question, bringing your total up to $4271
68. Answer 1 question, bringing your total up to $4721
69. Answer 1 question, bringing your total up to $5171
70. Answer 1 question, bringing your total up to $5621
71. Answer 1 question, bringing your total up to $6071
72. Answer 1 question, bringing your total up to $6521
73. Answer 1 question, bringing your total up to $6971
74. Answer 1 question, bringing your total up to $7421
75. Answer 1 question, bringing your total up to $7871
76. Buy the Level 5 ($500) money per question upgrade for $7500, making your total $371
77. Answer 1 question, bringing your total up to $2021
78. Answer 1 question, bringing your total up to $3671
79. Answer 1 question, bringing your total up to $5321
80. Answer 1 question, bringing your total up to $6971
81. Answer 1 question, bringing your total up to $8621
82. Answer 1 question, bringing your total up to $10271
83. Buy the Level 5 (5x) multiplier upgrade for $9000, making your total $1271
84. Answer 1 question, bringing your total up to $4021
85. Answer 1 question, bringing your total up to $6771
86. Answer 1 question, bringing your total up to $9521
87. Answer 1 question, bringing your total up to $12271
88. Answer 1 question, bringing your total up to $15021
89. Buy the Level 5 ($250) streak bonus upgrade for $15000, making your total $21
90. Answer 1 question, bringing your total up to $3771
91. Answer 1 question, bringing your total up to $7521
92. Answer 1 question, bringing your total up to $11271
93. Answer 1 question, bringing your total up to $15021
94. Answer 1 question, bringing your total up to $18771
95. Answer 1 question, bringing your total up to $22521
96. Answer 1 question, bringing your total up to $26271
97. Answer 1 question, bringing your total up to $30021
98. Answer 1 question, bringing your total up to $33771
99. Answer 1 question, bringing your total up to $37521
100. Answer 1 question, bringing your total up to $41271
101. Answer 1 question, bringing your total up to $45021
102. Answer 1 question, bringing your total up to $48771
103. Answer 1 question, bringing your total up to $52521
104. Answer 1 question, bringing your total up to $56271
105. Buy the Level 6 ($2000) money per question upgrade for $56250, making your total $21
106. Answer 1 question, bringing your total up to $11271
107. Answer 1 question, bringing your total up to $22521
108. Answer 1 question, bringing your total up to $33771
109. Answer 1 question, bringing your total up to $45021
110. Answer 1 question, bringing your total up to $56271
111. Answer 1 question, bringing your total up to $67521
112. Buy the Level 6 (8x) multiplier upgrade for $63750, making your total $3771
113. Answer 1 question, bringing your total up to $21771
114. Answer 1 question, bringing your total up to $39771
115. Answer 1 question, bringing your total up to $57771
116. Answer 1 question, bringing your total up to $75771
117. Answer 1 question, bringing your total up to $93771
118. Answer 1 question, bringing your total up to $111771
119. Answer 1 question, bringing your total up to $129771
120. Answer 1 question, bringing your total up to $147771
121. Answer 1 question, bringing your total up to $165771
122. Answer 1 question, bringing your total up to $183771
123. Answer 1 question, bringing your total up to $201771
124. Answer 1 question, bringing your total up to $219771
125. Answer 1 question, bringing your total up to $237771
126. Buy the Level 7 ($5000) money per question upgrade for $225000, making your total $12771
127. Answer 1 question, bringing your total up to $54771
128. Answer 1 question, bringing your total up to $96771
129. Answer 1 question, bringing your total up to $138771
130. Answer 1 question, bringing your total up to $180771
131. Buy the Level 6 ($1200) streak bonus upgrade for $150000, making your total $30771
132. Answer 1 question, bringing your total up to $80371
133. Answer 1 question, bringing your total up to $129971
134. Answer 1 question, bringing your total up to $179571
135. Answer 1 question, bringing your total up to $229171
136. Answer 1 question, bringing your total up to $278771
137. Answer 1 question, bringing your total up to $328371
138. Answer 1 question, bringing your total up to $377971
139. Answer 1 question, bringing your total up to $427571
140. Answer 1 question, bringing your total up to $477171
141. Answer 1 question, bringing your total up to $526771
142. Buy the Level 7 (12x) multiplier upgrade for $525000, making your total $1771
143. Buy the rebooter for $1535, making your total $236
144. Buy the mini bonus for $30, making your total $206
145. Buy the mega bonus for $65, making your total $141
146. Answer 1 question using the mini and mega bonuses, bringing your total up to $744141
147. Use the rebooter to regenerate your previously bought powerups.
148. Answer 1 question using the mini and mega bonuses, bringing your total up to $1488141
149. Answer 1 question, bringing your total up to $1562541
150. Buy the Level 7 ($65000) streak bonus upgrade for $1500000, making your total $62541
151. Answer 1 question, bringing your total up to $902541
152. Answer 1 question, bringing your total up to $1742541
153. Answer 1 question, bringing your total up to $2582541
154. Answer 1 question, bringing your total up to $3422541
155. Answer 1 question, bringing your total up to $4262541
156. Answer 1 question, bringing your total up to $5102541
157. Answer 1 question, bringing your total up to $5942541
158. Answer 1 question, bringing your total up to $6782541
159. Answer 1 question, bringing your total up to $7622541
160. Buy the Level 9 ($250000) money per question upgrade for $7500000, making your total $122541
161. Answer 1 question, bringing your total up to $3902541
162. Answer 1 question, bringing your total up to $7682541
163. Buy the Level 8 (18x) multiplier upgrade for $4875000, making your total $2807541
164. Answer 1 question, bringing your total up to $8477541
165. Answer 1 question, bringing your total up to $14147541
166. Answer 1 question, bringing your total up to $19817541
167. Answer 1 question, bringing your total up to $25487541
168. Answer 1 question, bringing your total up to $31157541
169. Answer 1 question, bringing your total up to $36827541
170. Answer 1 question, bringing your total up to $42497541
171. Answer 1 question, bringing your total up to $48167541
172. Answer 1 question, bringing your total up to $53837541
173. Answer 1 question, bringing your total up to $59507541
174. Answer 1 question, bringing your total up to $65177541
175. Answer 1 question, bringing your total up to $70847541
176. Answer 1 question, bringing your total up to $76517541
177. Buy the Level 10 ($1000000) money per question upgrade for $75000000, making your total $1517541
178. Answer 1 question, bringing your total up to $20687541
179. Answer 1 question, bringing your total up to $39857541
180. Answer 1 question, bringing your total up to $59027541
181. Buy the Level 9 (30x) multiplier upgrade for $48750000, making your total $10277541
182. Answer 1 question, bringing your total up to $42227541
183. Answer 1 question, bringing your total up to $74177541
184. Answer 1 question, bringing your total up to $106127541
185. Answer 1 question, bringing your total up to $138077541
186. Answer 1 question, bringing your total up to $170027541
187. Answer 1 question, bringing your total up to $201977541
188. Answer 1 question, bringing your total up to $233927541
189. Answer 1 question, bringing your total up to $265877541
190. Answer 1 question, bringing your total up to $297827541
191. Answer 1 question, bringing your total up to $329777541
192. Answer 1 question, bringing your total up to $361727541
193. Answer 1 question, bringing your total up to $393677541
194. Answer 1 question, bringing your total up to $425627541
195. Answer 1 question, bringing your total up to $457577541
196. Answer 1 question, bringing your total up to $489527541
197. Answer 1 question, bringing your total up to $521477541
198. Answer 1 question, bringing your total up to $553427541
199. Answer 1 question, bringing your total up to $585377541
200. Answer 1 question, bringing your total up to $617327541
201. Answer 1 question, bringing your total up to $649277541
202. Answer 1 question, bringing your total up to $681227541
203. Answer 1 question, bringing your total up to $713177541
204. Answer 1 question, bringing your total up to $745127541
205. Answer 1 question, bringing your total up to $777077541
206. Buy the Level 10 (100x) multiplier upgrade for $750000000, making your total $27077541
207. Answer 1 question, bringing your total up to $133577541
208. Answer 1 question, bringing your total up to $240077541
209. Answer 1 question, bringing your total up to $346577541
210. Answer 1 question, bringing your total up to $453077541
211. Answer 1 question, bringing your total up to $559577541
212. Answer 1 question, bringing your total up to $666077541
213. Answer 1 question, bringing your total up to $772577541
214. Answer 1 question, bringing your total up to $879077541
215. Answer 1 question, bringing your total up to $985577541
216. Answer 1 question, bringing your total up to $1092077541
217. Answer 1 question, bringing your total up to $1198577541
218. Answer 1 question, bringing your total up to $1305077541
219. Answer 1 question, bringing your total up to $1411577541
220. Answer 1 question, bringing your total up to $1518077541
221. Buy the Level 10 ($1000000) streak bonus upgrade for $1500000000, making your total $18077541

Please note that neither this script nor its author are associated with the Gimkit company or any Gimkit employee in any way. I am simply a student who used Gimkit in high-school and wanted to calculate the optimal strategy for completing Gimkit assignments.

Documentation coming soon!
