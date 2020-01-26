# Deep-Fashion

With recent advancements in clothing recognition techniques, DeepFashion digs itself an ever-growing scope. Taking DeepFashion as its basis, our project aims to provide a way for the customer to simply stand in front of his/her wardrobe and watch clothes switch themselves on a real-time clicked image of them. By using machine learning techniques, we hope to predict the looks each apparel would present, making it easier for the user to pick the right outfit without going through the hassle of physically trying on multiple outfits. Ticking the above boxes, we should be able to bring the effort of physically running in and out of the changing room and remembering each look and comparing, the whole of this tiresome process to simply swiping looks as one does while shopping online.

The aim of the project is to :
- Make choosing outfit for a specific occasion or a casual day a process, as easy as swiping pictures on a screen.
- Make the system user-friendly, light and giving satisfying and accurate enough to judge and compare multiple looks.
- Ensure the cameras are fitted at the right angles to click a good pose for the user view and judge outfit.
- Build a prototype that demonstrates the user interface on a small scale in order to get early feedback from the customer/users.

This project is an attempt to apply deep learning and robotics to devise a solution that will provide instant looks virtually by scanning the user’s body dimensions. The user will thus be able to simply swipe through the looks and choose the best option for him/her. A couple of cameras will be fitted at appropriate locations to capture images in accurate poses. The entire module will be run on Raspberry Pi to facilitate an independent and self-sufficient system for the user. The user stands at the fixed spot, where the corresponding camera clicks the user at appropriate poses and the input image is loaded along with the store’s entire dataset of apparels, where the user will be shown how each outfit looks on him/her with the use of the input image.

Given three input images: human wearing cloth A, stand-alone cloth A and stand-alone cloth B, the Conditional Analogy GAN (CAGAN) generates a human image wearing cloth B. CAGAN is combines with StackGan-v2 to generate high quality texture/graphics and also stabilize training.

After training, the generator and discriminator should together be able to output an image with accuracy good enough for the user to be able to judge the looks each outfit would deliver.

