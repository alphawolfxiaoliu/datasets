
MNIST��һ�����ŵġ�����ǩ����д���������ݿ⣬������ѵ�����Ͳ��Լ������֡����У�ѵ������60000��28*28�ߴ����д�����ֻҶ�ͼƬ�������Լ���10000��ͬ�����ʵ�ͼƬ���ڱ����У�ÿ��ͼƬ�ɱ�ʾ��һ��28*28�����о��󣬲����䰴����չ��һ��784*1����������Ȼ�������һλ������Ӹ�ͼƬ������ǩ�����һ��785*1�����������ʴˣ�MNIST���ݼ����Ա����һ��785*60000+785*10000��ѵ����+���Լ����߶ȵľ���ÿһ��ǰ784����һ����д���������������1λ�Ǹ������ı�ǩ���������ݲο�mnist.mat�ļ���train=��785*60000����test=��785*10000����pic_rows=28,pic_cols=28��

The MNIST database is a public large database of handwritten digits, which are allocated manually supplied labels and divided into training and testing parts respectively. More specifically, the training set holds 60000 grayscale pictures with 28*28 dimensions for each, while there are 10000 images accordingly in the testing part. In this article, each handwritten digit picture would be represented to a 28*28 matrix, and further be reshaped to a 784*1 vector; and then convert each vector into 785*1 shape by putting corresponding label on its bottom. Consequently, the whole handwritten digit corpus equates to two separate matrices: 785*60000 (training set) and 785*10000 (testing set), and each column represents one handwritten digit image. The concrete digital dataset is coded in mnist.mat with variables train (785*60000), test(785*10000), pic_rows (28), and pic_cols (28).

For more information, you can refer to http://yann.lecun.com/exdb/mnist/.


