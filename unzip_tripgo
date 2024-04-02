import subprocess

def unzip_tripgo():
    try:
        subprocess.run(['unzip', 'tripgo'], check=True)
        print("Command executed successfully.")
    except subprocess.CalledProcessError as e:
        print(f"Error: {e}")

if __name__ == "__main__":
    unzip_tripgo()
