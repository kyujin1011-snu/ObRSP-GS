# ObRSP-GS : Opacity based Random Smooth Pruning Gaussian Splatting

Lim Kyu Jin

kyujin1011@snu.ac.kr


I used colab environment

https://colab.research.google.com/drive/1IoXVzjEd6CEtAtPTLZYB_YjOUKFzExTh?usp=sharing

Run cells until under the image cell

![image](https://github.com/user-attachments/assets/bd89af37-3d06-4787-90fd-80d5ec762c89)

This is our hard pruning original setting

--mode 2 : mode 0 means 3D-GS(not ours), mode 1 means not using smooth pruning, mode 2 means using smooth pruning

--afterremove 1 : afterremove 0 means softpruning, afterremove 1 means hardpruning

--remove_start_iter 5000 8000 11000 15000 18000 21000 : pruning iteration

--remove_tres 0.50 : pruning opacity threshold

--prob 0.8 : pruning probability before iteration 15000

--afterprob 0.5 : pruning probability after iteration 15000 and at 15000 

--eval : eval means distinguish train image set and test image set


Notice: sometimes "세션다시시작" error occurs in the first cell. click "세션다시시작" and restart please. 
