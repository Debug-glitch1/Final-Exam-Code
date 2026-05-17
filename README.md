# Final-Exam-Code
def ask_sibling_names(count):
    for i in range(1, count + 1):
        input()
    
def main():
    try:
        siblings = int(input())
    except:
        return

    if siblings < 0:
        print("I don't know what to say about that.")
        
    elif siblings == 0:
        print("I didn't know you were an only child.")

    elif 1 <= siblings <= 3:
        print("A moderate-size family.")
        ask_sibling_names(siblings)
