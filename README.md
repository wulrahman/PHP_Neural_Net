# PHP_Neural_Net
A Neural Net, The Fruits of my labour
This is using the chain rule for back propagation,
WEHRE (change)Etotal/(change)WeightK[n] = (change)Etotal/(change)YPredicted
* (change)YPredicted/(change)Net_Out
* (change)Net_Out/(change)Weight[n]

Etotal = 1/N(sum(Yactual - Ypredicted[n])^2)
sum 0 to N

Ypredicted = activation_function(Net_out)
Ypredicted/Net_out = derivative_activation_function(Net_out)

Net_out = (WeightK1)Out_K1 + (WeightK2)Out_K2 + (WeightK3)Out_K3 + (WeightK4)Out_K4 + (WeightK5)Out_K5

(change)Net_out/(change)WeightK[n] = Out_K[n]

Net_Out = (WeightK1)Out_K1 + (WeightK6)Out_K2 + (WeightK11)Out_K3 + (WeightK16)Out_K4 + (Weightk21)Out_K5

(change)Net_Out/(change)WeightK[N] = (WeightK1)Out_K[n]

WEHRE (change)Etotal/(change)Net_Out = (change)Etotal/(change)YPredicted
* (change)YPredicted/(change)Net_Out

Please note the above is only true at the last layour

After Which, 

WEHRE (change)Etotal/(change)WeightJ[n] = (change)Etotal/(change)Net_Out
* (change)Net_K/(change)Out_K
* (change)Out_K/(change)NetJ
* (change)NetJ/(change)WeightJ[n]

You get the idea
