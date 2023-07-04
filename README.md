Bài toán phân loại hình ảnh là một trong những bài toán phổ biến nhất trong Computer Vision. Nhiệm vụ của bài toán này là phân loại một hình ảnh đầu vào (input) thành một nhãn (label) đầu ra (output).

Giới Thiệu Về Bộ Dữ Liệu

CIFAR-10 là bộ dữ liệu về thị giác máy tính rất phổ biến. Bộ dữ liệu này đã được nghiên cứu kỹ lưỡng trong nhiều loại mô hình Deep learning phục vụ cho nhận dạng đối tượng.

Bộ dữ liệu này bao gồm 60.000 hình ảnh được chia thành 10 target classes, với mỗi class chứa 6000 hình ảnh có kích thước 32 x 32.

Bộ dữ liệu này chứa các hình ảnh có độ phân giải thấp (32 x 32), cho phép các researchers thử các thuật toán mới. 10 lớp khác nhau của tập dữ liệu này là

Airplane

Car

Bird

Cat

Deer

Dog

Frog

Horse

Ship

Truck

CIFAR-10 đã có sẵn trong datasets module của Keras, chúng ta chỉ việc import trực tiếp từ keras.datasets.
