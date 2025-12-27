from datetime import datetimE

def log_activity():
    now = datetime.now()
    return f"Daily commit done at {now.strftime('%Y-%m-%d %H:%M:%S')}"

if __name__ == "__main__":
    print(log_activity())
