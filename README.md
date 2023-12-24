# VITA_PYTHON_PROJECT
Encoder decoder 
**Project Description: Message Encode and Decode Tool**

This Python script provides a simple graphical user interface (GUI) for encoding and decoding messages using a key. The tool uses the Tkinter library for the GUI and includes base64 encoding and decoding functionality.

### Features:
1. **Encode Functionality:** Allows users to encode a message using a key. The encoding process involves iterating through each character in the message and performing a mathematical operation using the corresponding character in the key. The result is then base64 encoded.

2. **Decode Functionality:** Enables users to decode a previously encoded message using the same key. The decoding process involves base64 decoding the message and then reversing the mathematical operation applied during encoding.

3. **Mode Selection:** Users can specify the mode of operation ('e' for encode or 'd' for decode). The mode determines whether the tool should encode or decode the input message.

4. **User Interface:** The GUI includes input fields for the message and key, a mode selection entry, and an output field to display the result. Buttons are provided to trigger the encoding/decoding process, reset the input fields, and exit the application.

### How to Use:
1. **Message Input:** Enter the message you want to encode/decode in the 'MESSAGE' input field.

2. **Key Input:** Enter the key to be used for encoding/decoding in the 'KEY' input field.

3. **Mode Selection:** Specify the mode of operation ('e' for encode or 'd' for decode) in the 'MODE' input field.

4. **Result Display:** The result of the encoding/decoding operation will be displayed in the 'RESULT' field.

5. **Buttons:**
    - **RESULT Button:** Click to trigger the encoding/decoding process based on the provided input.
    - **RESET Button:** Click to reset all input fields to their default state.
    - **EXIT Button:** Click to exit the application.

### Usage Example:
1. Encode a Message:
   - Message: "Hello World"
   - Key: "key123"
   - Mode: 'e'
   - Result: "Encoded Message"

2. Decode a Message:
   - Message: "Encoded Message"
   - Key: "key123"
   - Mode: 'd'
   - Result: "Hello World"

### Note:
- Ensure that the mode is set to 'e' for encoding and 'd' for decoding.
- The key used for encoding must be used for decoding to retrieve the original message.

Feel free to use and modify this tool for your encoding and decoding needs. If you encounter any issues or have suggestions for improvement, please provide feedback.
