# Gun Detection with YOLOv5

A computer vision notebook that detects firearms in images using a YOLOv5 object detector, with an additional LSTM-based classification experiment.

## What the notebook covers

- Dataset preparation: organising images and YOLO-format label files into the expected folder structure, and creating empty label files for images without annotations
- Loading a YOLOv5 model and running inference on a single image or a whole folder
- Drawing bounding boxes and GUN / NO GUN labels on the images and saving the annotated results
- Filtering images based on the detection result
- An LSTM classifier built with TensorFlow/Keras, evaluated with accuracy, a classification report and a confusion matrix

## Tech stack

Python, PyTorch, YOLOv5, TensorFlow/Keras, scikit-learn, Pillow, Matplotlib, Seaborn

## Setup

The notebook is written for Google Colab with a GPU runtime.

1. Open `gun_detection.ipynb` in Colab.
2. Mount Google Drive and set the dataset and model paths in the first cells.
3. The notebook clones the YOLOv5 repository if it is not already present.
4. Run the cells in order.

## Notes

- Notebook outputs are cleared, and the dataset and trained weights are not included in this repository.
- Intended for research and safety-focused computer vision work. Only use data you are authorised to use.