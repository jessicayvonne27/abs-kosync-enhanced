git clone https://github.com/jessicayvonne27/abs-kosync-enhanced.git
cd abs-kosync-enhanced

git clone https://github.com/cporcellijr/abs-kosync-bridge.git
cd abs-kosync-enhanced


# Build
docker build -t abs-kosync-enhanced:latest .

# Run
docker compose up -d

git remote set-url origin http://github.com/YOU/YOUR_REPO