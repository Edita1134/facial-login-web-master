from your_module import add_user_img_path  # Import the function from your module

# Assuming you have your database and Face Recognition model initialized
# user_db = initialize_user_database()
# FRmodel = initialize_face_recognition_model()

# Registering image paths for a person named "John"
name = "John"
img_path = "path/to/john_image.jpg"  # Replace with the actual file path of John's image
add_user_img_path(user_db, FRmodel, name, img_path)
