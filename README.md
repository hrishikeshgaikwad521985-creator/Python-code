# Python-code
def file_demo():     try:         f = open("test.txt", "w")         f.write("Hello Python")         f.close()          f = open("test.txt", "r")         print(f.read())         f.close()      except Exception:         print("Error occurred")  file_demo()
