Surge sway, yaw
fram, sida, vinkel

https://github.com/cybergalactic/FossenHandbook/tree/main?tab=readme-ov-file The goat av navigasjon
https://www.dropbox.com/scl/fi/68ky3k4is0gahpxi3h010/Ch14.pdf?rlkey=6yq5djch0ycna9h69qz6xh4lz&e=1&dl=0 slide 56
https://drive.google.com/file/d/1K1RxgbNbvrErOX3CBtbcIcriACYm9Sm6/view slide 31



![[Pasted image 20260208150943.png]]


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



# IMU calculations

Correction of accelerometer
![[Pasted image 20260226131019.png]]


![[Pasted image 20260302114108.png]]
Proof of Kalman filter "fungerer"




 \begin{equation} 
 p_{k+1} = p_{k} + \Delta t \cdot v_{k} + \frac{(\Delta t)^2}{2} \cdot a_{k}

 \end{equation} 


 \begin{equation} 
 v_{k+1} = v_{k} + \Delta t *(a_{k}+b_{k})
 \end{equation} 

 \begin{equation} 
 b_{k+1} = b_{k}


 \end{equation} 


 \begin{equation} 
 y_{k} = p_{k}
 \end{equation} 

 \begin{equation} 
 x = \text{atan2} (v_{k}[1],v_{k}[0])     
 \end{equation} 
