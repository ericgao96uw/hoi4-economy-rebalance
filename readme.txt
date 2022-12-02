Adjust each economy law's effect, some economy law's effect will dynamically change based on war support.

调整了每个经济法案的效果，部分经济法案的效果将会根据战争支持度动态变化。

Defines:
- War exhaustion. Which equals to -1 + war_support. Always negative, range = [-1, 0]. e.g for a country that has 0.3 (30%) war support, then its war exhaustion = -0.7 (-70%). The war exhaustion will have negative effect on a country.

定义：
- 厌战度：等于 -1 + 战争支持度，总是为负，取值范围为[-1, 0]。例如如果一个国家的战争支持度为0.3 (30%), 那么它的厌战度则为-0.7 (70%), 厌战度对国家会有负面影响。

Details:
- Partial Mobilization: Will mildly reduce daily political power gain based on war support. Reduced daily political power gain depends on war exhaustion and its government. Fascism and communism will have less negative effect factor.
- War Economy: Will moderately reduce daily political power gain and weekly stability based on war exhaustion and its government. Fascism and communism will have less negative effect factor.
- Total Mobilization: Will significantly reduce daily political power gain and weekly stability based on war exhaustion. No matter what's government it is.

细节：
- 部分动员：将会根据厌战度，意识形态和战争性质轻微的减少每日政治点数的获得。法西斯主义和共产主义政府将会受到更小的影响。防御战争将不会受到负面影响。
- 战时经济： 将会根据厌战度，意识形态和战争性质适度的减少每日政治点数的获得和每周稳定度。法西斯主义和共产主义政府将会受到更小的影响。防御战争将不会受到负面影响。若处于和平状态，也会受到负面影响
- 总动员：将会根据厌战度，意识形态和战争性质严重的减少每日政治点数的获得，不论国家属于何种意识形态。防御战争将不受负面影响。若处于和平状态，会受到严重的负面影响


以上战争支持度的影响将会每月刷新，若更换上述法案（如切换至民用经济）， 则会立刻移除这些修正。