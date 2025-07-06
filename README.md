## 📸 Simple Image Stack

A lightweight PHP web application that fetches and displays high-quality images using the Pexels API. Users can search for images, preview them in a modal, and download them directly. Built with PHP, Bootstrap, and JavaScript.

---

### 🚀 Features

- 🔍 Keyword-based image search
- 🖼️ Responsive image grid layout
- 🪟 Modal preview with photographer info
- 📥 One-click image download
- 📱 Mobile-friendly design
- ⚡ Powered by the [Pexels API](https://www.pexels.com/api/)

---

### 📂 Project Structure

```
php-image-stack/
├── index.php              # Main application file
├── script.js              # JavaScript for modal and preview
├── style.css              # Custom styles (optional)
├── stackAPI.class.php     # PHP class for handling Pexels API requests
├── gallery.jpg            # Sample image (optional)
```

---

### 🛠️ Requirements

- PHP 7.4 or higher
- cURL enabled
- A free [Pexels API key](https://www.pexels.com/api/)

---

### ⚙️ Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/davidfrancisasuah/php-image-stack.git
   cd php-image-stack
   ```

2. **Add your Pexels API key:**

   Open `stackAPI.class.php` and replace the placeholder with your actual API key:

   ```php
   private $apiKey = 'YOUR_PEXELS_API_KEY';
   ```

3. **Run the app:**

   Place the folder in your local server directory (e.g., `htdocs` for XAMPP) and open:

   ```
   http://localhost/php-image-stack/
   ```

---

### 📸 Screenshots



#### 🪟 Modal Preview
![Modal Preview](https://github.com/davidfrancisasuah/php-image-stack/blob/master/index1.jpeg)
![Modal Preview](https://github.com/davidfrancisasuah/php-image-stack/blob/master/index2.jpeg)
![Modal Preview](https://github.com/davidfrancisasuah/php-image-stack/blob/master/index3.jpeg)
![Modal Preview](https://github.com/davidfrancisasuah/php-image-stack/blob/master/index4.jpeg)
![Modal Preview](https://github.com/davidfrancisasuah/php-image-stack/blob/master/index5.jpeg)
![Modal Preview](https://github.com/davidfrancisasuah/php-image-stack/blob/master/index6.jpeg)


---

### 📄 License

This project is open-source and for educational purposes only..

