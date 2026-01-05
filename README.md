# Logic Gate Classification with Neural Networks

This repository contains an implementation of a Multi-Layer Perceptron (MLP) to solve basic logical problems: AND, OR, and XOR. The project demonstrates the capability of neural networks to handle both linearly separable and non-linearly separable data.

## Author

* Nukri Munjishvili

## Project Overview

The main objective of this project is to illustrate the "XOR Problem" in machine learning. While AND and OR gates can be solved with a simple linear classifier, the XOR gate requires a non-linear decision boundary. This project uses `MLPClassifier` from Scikit-Learn to solve this by utilizing a hidden layer.

## Technical Details

### Libraries Used

* **NumPy:** For data structure and array manipulation.
* **Matplotlib:** For visualizing decision boundaries and data points.
* **Scikit-Learn:** For the `MLPClassifier` model.

### Model Architecture

* **Algorithm:** Multi-Layer Perceptron (MLP).
* **Hidden Layers:** One hidden layer with 4 neurons.
* **Activation Function:** ReLU (Rectified Linear Unit).
* **Optimization:** The model is trained to classify standard truth tables for logical operations.

## Results

The notebook generates visualization plots showing the decision boundaries for each logic gate:

1. **AND & OR:** Shows a linear boundary (straight line).
2. **XOR:** Shows a non-linear boundary (curved/complex), proving the necessity of the hidden layer.

## How to Run

1. Ensure Python and the required libraries are installed.
2. Open `Code File.ipynb` in Jupyter Notebook.
3. Run the cells sequentially to train the models and view the visualizations.

---

# ლოგიკური ფუნქციების კლასიფიკაცია ნეირონული ქსელებით

ეს რეპოზიტორია მოიცავს მრავალშრიანი პერცეპტრონის (MLP) იმპლემენტაციას ლოგიკური ამოცანების გადასაჭრელად: AND, OR და XOR. პროექტი აჩვენებს ნეირონული ქსელების უნარს, იმუშაონ როგორც წრფივად განცალკევებად, ისე არაწრფივ მონაცემებთან.

## ავტორი

* ნუკრი მუნჯიშვილი

## პროექტის მიმოხილვა

პროექტის მთავარი მიზანია მანქანურ სწავლებაში ცნობილი "XOR პრობლემის" ილუსტრირება. თუ AND და OR ფუნქციების ამოხსნა შესაძლებელია მარტივი წრფივი კლასიფიკატორით, XOR მოითხოვს არაწრფივ გადაწყვეტილების საზღვარს. აღნიშნული პრობლემის გადასაჭრელად გამოყენებულია Scikit-Learn-ის `MLPClassifier` და ფარული შრე (Hidden Layer).

## ტექნიკური დეტალები

### გამოყენებული ბიბლიოთეკები

* **NumPy:** მონაცემთა სტრუქტურებისა და მასივების დასამუშავებლად.
* **Matplotlib:** გადაწყვეტილების საზღვრებისა (Decision Boundaries) და მონაცემთა ვიზუალიზაციისთვის.
* **Scikit-Learn:** `MLPClassifier` მოდელის გამოსაყენებლად.

### მოდელის არქიტექტურა

* **ალგორითმი:** Multi-Layer Perceptron (MLP).
* **ფარული შრეები:** ერთი ფარული შრე 4 ნეირონით.
* **აქტივაციის ფუნქცია:** ReLU.
* **ოპტიმიზაცია:** მოდელი სწავლობს სტანდარტული ლოგიკური ჭეშმარიტების ცხრილების მიხედვით.

## შედეგები

კოდის გაშვების შედეგად იქმნება გრაფიკები, რომლებიც აჩვენებს თითოეული ლოგიკური ელემენტის საზღვრებს:

1. **AND & OR:** აჩვენებს წრფივ საზღვარს (სწორ ხაზს).
2. **XOR:** აჩვენებს არაწრფივ საზღვარს, რაც ადასტურებს ფარული შრის საჭიროებას.

## გაშვების ინსტრუქცია

1. დარწმუნდით, რომ დაინსტალირებული გაქვთ Python და საჭირო ბიბლიოთეკები.
2. გახსენით `Code File.ipynb` Jupyter Notebook-ში.
3. გაუშვით უჯრები თანმიმდევრობით, რათა დაატრენინგოთ მოდელები და ნახოთ ვიზუალიზაციები.
