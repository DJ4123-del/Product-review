<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Review Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77aaff 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        nav ul {
            padding: 0;
            list-style: none;
        }
        nav ul li {
            display: inline;
            margin: 0 5px;
        }
        .review-form {
            background: #fff;
            padding: 20px;
            margin-top: 30px;
        }
        .review-form h2 {
            margin-bottom: 20px;
        }
        .review-form .form-group {
            margin-bottom: 15px;
        }
        .review-form .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .review-form .form-group input,
        .review-form .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
        }
        .review-form button {
            display: inline-block;
            background: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .reviews {
            margin-top: 30px;
        }
        .review {
            background: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Product Review</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Reviews</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container">
        <div class="review-form">
            <h2>Leave a Review</h2>
            <form>
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name">
                </div>
                <div class="form-group">
                    <label for="review">Review:</label>
                    <textarea id="review" name="review" rows="5"></textarea>
                </div>
                <button on click="submitReview()">Submit</button>
            </form>
        </div>

        <div class="reviews">
            <h2>Reviews</h2>
            <div class="review">
                <p><strong>John Doe:</strong> This is a great product!</p>
            </div>
            <div class="review">
                <p><strong>Jane Smith:</strong> I wasn't too impressed with this product.</p>
            </div>
        </div>
    </div>
</body>
</html>
