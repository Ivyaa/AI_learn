# AI_learn
The working diary ~

# 8/11
1. 環境設定果然是每到一個新地方的大問題，因為最開始暫時沒有電腦的原因，所以先把自己的筆電重新開了一個WSL2
2. 安裝WSL就遇到大麻煩，可能是WIN10太久沒更新的緣故，會遇到奇怪的錯誤代碼(並非沒有開啟Visualization)
3. 解決順序：WSL update --> WSL install --> WSL convert to WSL2 --> install Ubuntu
4. 請根據想要的python基礎版本來選定Ubuntu版本，尤其是不考慮使用miniconda或conda系列可以輕鬆解決環境問題的套件，原先使用Ubuntu 20.04(Python=3.8)，嘗試更新到Python=3.10無法覆蓋原本的Python版本，google上常見的更改PATH方法也行不通。

### Learning
Transformer: encoder + decoder (sequence to sequence); Unlike RNN and CNN, word to word.
<br>透過找尋最高分的輸出序列(Loss總和最小)，來達成學習目標。</br>
<br>url: https://www.youtube.com/watch?v=N6aRv06iv2g</br>
<br>url: https://www.youtube.com/watch?v=nzqlFIcCSWQ</br>

# 8/12
1. WIN11沒更新會阻擋創立WSL2
2. 了解了階層式程式架構
3. Gemini CLT蠻好用的，用來整理程式邏輯跟理解是真的很有東西

### Learning
GAN 理論教學 url:https://www.youtube.com/watch?v=4OWp0wDu6Xw
