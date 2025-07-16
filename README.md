def chatbot():
  print("Chatbot: Hello! Type your message (ji! , how are you! ,thanks!, good bye!).")

  while True:
  user_input = input("You: ").lower()

  if user_input = "hi!":
     print("Chatbot: Hi!")

  elif user_input = "how are you!":
    print("Chatbot: I am fine!")

  elif user_input = "thanks!":
    print("Chatbot: Good bye!")
    break

  elif user_input == "good bye!":
    print("Chatbot: Good bye!")
    break

  else: 
    print("Chatbot: I can only respond to 'hi!', 'how are you!', 'thanks!', or 'good bye!'.")

# run the chatbot
chatbot()



