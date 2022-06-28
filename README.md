# swift-ml

# SuperVised Learning
Ogni dato che si da in input ha una label
che specifica il dato.

Es : Immagine di un cane con scritto cane.

Es : Immagine di un gatto con scritto gatto.


# UnsuperVised Learning

Non si hanno label sui dati,
la macchina deve capire la struttura da se.

Un esempio è il custering.
Modelli di classificazione


# Reinforcement Learning



# CoreML

1. Load a Pre-Trained Model
2. Make Predictions

https://developer.apple.com/machine-learning


Classification or Regression.

In CoreML, non è possibile fare Training.
ho degli static model( pre-trained model ),
No Encryption.

Possibilità di Conversione da :
Caffe , keras a ML-MODEL


Documentazione :
https://developer.apple.com/machine-learning/models/


Incorporate il file di training .mimodel



class ViewController : UIViewController , UIImagePickerControllerDelegate, UINavigationControllerDelegate {


  let imagePicker = UIImagePickerController()
  
  override func viewDidLoad(){
    super.viewDidLoad()
    
    imagePicker.delegate = self
    imagePicker.sourceType = .camera
    imagePicker.allowsEdition = false
  }
  
}

Documentazione Su SwiftUI : Take photos in SwiftUI

https://medium.com/swlh/how-to-open-the-camera-and-photo-library-in-swiftui-9693f9d4586b








