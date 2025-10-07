# gaustudio_0_main_requirements
## Main requirements

### 

Python >= 3.8
torch1.12.1+cu113 and torch2.0.1+cu118

# Combined Commands Example

```text
# --- Bash ---
cd /workspace/my_project
ls -la
bash setup.sh

# --- Python ---
def greet(name):
    print(f"Hello, Jacky!")

greet("Jacky")

def add(a, b):
    return a + b

print(add(5, 7))

# --- PostgreSQL ---
-- Connect to database
psql -U postgres -d mydb
-- Create table
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name VARCHAR(50)
);
-- Insert data
INSERT INTO users (name) VALUES ('Jacky');
-- Query data
SELECT * FROM users;
