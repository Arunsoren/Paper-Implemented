the paper that started it all :  https://arxiv.org/abs/1706.03762

the best explanation :  https://www.youtube.com/watch?v=4Bdc55j80l8&t=5s

self / cross, hard / soft attention : https://www.youtube.com/watch?v=fEVyfT-gLqQ&t=536s

Attention: 

![Attent-1](https://github.com/Arunsoren/Paper-Implemented/assets/31899874/3a391f20-71ee-47ca-89f0-fe9dd5b67707)

![Attent-2](https://github.com/Arunsoren/Paper-Implemented/assets/31899874/6e5caa0f-1e3e-48a8-984b-81a356a8372d)

![Attent-3](https://github.com/Arunsoren/Paper-Implemented/assets/31899874/95aebc55-7c53-4f1d-994e-971781fb41d4)

output is :  512(64*8) x max sequence length 
output  will pass to Add & norm layer. 
also d_model is 512 so the size of  input and output will be same (30 x 200 x 512)
                                                 (batch_size x max_sequence_length x d_model(512)/multihead(512(64*8)))
