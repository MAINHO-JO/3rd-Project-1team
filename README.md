# 3re-Project-1team
 
1.
Epoch : 27/55....... Train Loss : 0.641 Valid Loss : 0.952 Valid Accuracy : 0.684

learning rate=0.001
batchsize = 16
epochs=55

데이터 전처리 이전방식
transforms.Compose([transforms.Resize([224, 224]), transforms.ToTensor(),transforms.Normalize((0.5, 0.5, 0.5), (0.5, 0.5, 0.5))])


2.
learning rate=0.00001
batchsize = 16
epochs=55
Epoch : 54/55....... 

Train Loss : 1.491 Valid Loss : 1.509 Valid Accuracy : 0.536


3.
learning rate=0.001
batchsize = 32
epochs=55

Epoch : 38/55....... Train Loss : 0.549 Valid Loss : 0.878 Valid Accuracy : 0.695


4.데이터 전처리 방식 바꿈
Epoch : 50/55....... Train Loss : 0.562 Valid Loss : 0.902 Valid Accuracy : 0.708


5.transform horizontal,verticalflip 추가
Epoch : 44/55....... Train Loss : 0.734 Valid Loss : 0.820 Valid Accuracy : 0.724
trigger :  8



6.clahe 추가

Epoch : 55/55....... Train Loss : 0.790 Valid Loss : 0.930 Valid Accuracy : 0.692
