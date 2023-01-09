# Paula
import matplotlib.pyplot as plt
import random

# funkcja losowanie na Y
#y = 2x + b
X = [(i+1 or i-1) for i in range(100,10000)]
Y = [random.randint(-80,-50) for i in X]
plt.ylabel('Intensity (dB)')
plt.xlabel('Frequency (Hz)')
plt.title
plt.plot(Y,'b')
plt.xlim(10,10000) 
plt.ylim(-70, 0)
plt.title('Wykres białego szumu')
plt.show()
