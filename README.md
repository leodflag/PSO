# PSO
粒子群演算法（PSO演算法）

# 虛擬碼
##### a.	產生N個粒子的各自亂數初始位置以及初始速度
##### b.	設定適應函數
##### c.	計算適應值，並將第一代群體和個體最佳先存起來
##### d.	計算適應值
##### e.	群體最佳值更新
##### f.	個體最佳值更新
##### g.	速度更新與調整
##### h.	位置更新與調整
##### i.	印出群體最佳值
##### j.	重複d-i  迭代itera次

# PSO參數的設置、調控
##### adapt_fun(x,v,N)：適應函數，x為位置，v為速度，N為粒子數
##### N：粒子數，10~20個
##### c0 、c1：常數，設2.0
##### Vmax：最大速度，以粒子範圍為大小，設200
##### w ：慣性權重，採線性遞減的慣性權重，從0.9線性遞減到0.4
##### 決定終止條件：迭代300次
