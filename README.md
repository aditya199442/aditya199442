# Create an HTML file with the given message

html_content = """<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorry Message</title>
    <style>
        body { font-family: Arial, sansserif; text-align: center; padding: 50px; background-color: #f8f8f8; }
        .message-box { background: white; padding: 20px; border-radius: 10px; box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1); display: inline-block; }
        h2 { color: #d32f2f; }
        p { font-size: 18px; line-height: 1.5; }
    </style>
</head>
<body>
    <div class="message-box">
        <h2>Hey CHAHAT,</h2>
        <p>मुझे सच में बहुत अफसोस है अगर मेरी किसी भी बात या हरकत से तुम्हें दुख पहुंचा हो। यह कभी भी मेरी मंशा नहीं थी, और मैं महसूस कर सकता हूँ कि मैंने तुम्हें तकलीफ दी है। तुम मेरे लिए बहुत खास हो, और मैं सच में चाहता हूँ कि सब कुछ पहले जैसा ठीक हो जाए। अगर मुझसे कोई गलती हुई है, तो मुझे माफ कर दो। मैं आगे से और बेहतर रहने की कोशिश करूंगा।</p>
    </div>
</body>
</html>
"""
# Save the HTML file
file_path = "/mnt/data/sorry_message.html"
with open(file_path, "w", encoding="utf-8") as file:
    file.write(html_content)

file_path

