CC=g++
LFLAGS=-lpthread -lopencv_highgui -lopencv_core -lopencv_imgproc -lopencv_calib3d -lopencv_features2d -lopencv_nonfree -lopencv_legacy

#estimateF:
#	$(CC) -o estimateF estimateF.cpp $(LFLAGS)
robustmatching:
	$(CC) -o robustmatching robustmatching.cpp $(LFLAGS)
#calibrate: CameraCalibrator.o
#	$(CC)  -o calibrate calibrate.cpp CameraCalibrator.o $(LFLAGS)

#CameraCalibrator.o:
#	$(CC)  -c CameraCalibrator.cpp $(LFLAGS)  

clean:
#	rm -rf calibrate CameraCalibrator.o
#	rm -rf estimateF 
	rm -rf robustmatching
