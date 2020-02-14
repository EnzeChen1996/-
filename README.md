#pytorch中 torch.mm 与 torch.matmul的区别
torch.mm()#执行矩阵乘法操作，不进行广播，当两张量维度不一致时报错
torch.matmul()#维度不一致时执行广播机制
