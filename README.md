# MaskDetectionCv2

The main aim of this model is to detect whether a person is wearing a mask or not...we can add this to production with help of CCTV cameras,which generate image of the the person it
sees and then if the person is not wearing a mask he/she will not be granted permission to enter that place...

======================================================================================================================================================================

»Generation of images by ------> CCTV cameras

»the trained model predicts whether the person is wearing a mask or not

»based on the result the entrance door,can be controlled by an IOT device which will open if the person is wearing mask and will show an Alert Message if 
the Person is not wearing a Mask stating "Please Wear a Mask"

======================================================================================================================================================================

here,i've created a Convolution Neural Network which detects whether the person is wearing a Mask or Not.
I've used the cv2 package of python for the DataPreprocessing and then i've passed those preprocessed images to a Convolution Neural Network which predicts whether the Person is Wearing a Mask or not
i've tried out for different configuration of images of sizes < 224X224,112X112,100X100 >pixels and the best result was produced by 112 X 112...the h5 file for the trained model was huge..
so i couldn't upload it:( 
