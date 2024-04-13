
# Fall Detection System

This project is a fall detection system implemented using Python and various libraries such as OpenCV, cvzone, and ultralytics YoloV8. It detects falls in a video stream using Yolov8 object detection and sends a notification via Telegram when a fall is detected.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sriram2226/AlertWatch-Fall-Detection-System-.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. NOTE : Create your own Telegram Bot using Botfather token in telegram and paste the your bot token and chat_id in main.py's designated variable

## Usage

1. Run the `main.py` script:

   ```bash
   python main.py
   ```

2. Press 't' to exit the application.

## Configuration

- `fall.mp4`: Input video file containing test footage to be analyzed.
- `telegram_bot_token`: Telegram bot token used for sending notifications 
[create your own bot and feed the bot token to get message to your phone].
- `chat_id`: Chat ID of the recipient for Telegram notifications.

## Dependencies

- OpenCV
- cvzone
- ultralytics YOLO
- requests



## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

## Credits

- [OpenCV](https://opencv.org/)
- [cvzone](https://github.com/cvzone/cvzone)
- [Ultralytics YOLO](https://github.com/ultralytics/yolov5)

