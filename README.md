# คำสั่ง Docker 
## คำสั่งเกี่ยวกับ images
## คำสั่งเกี่ยวกับ volume
## คำสั่งเกี่ยวกับ container
- docker version = ตรวจดูเวอร์ชั่น
- docker images = ดู Dockerimage ที่ถูกสร้าง
- docker volume ls = ดู Volume ที่สร้างขึ้นมาทั้งหมด
- docker system df = ตรวจสอบเนื้อที่ที่ Docker ใช้
- docker build -t [ชื่อimage] = สร้าง Dockerimage
- docker run [ชื่อimage] = Run Dockerimage
- docker ps -a = ดู Container และ Status ของ Container
- docker history [ชื่อimage] = ดูประวัติของ Dockerfile
- docker system df = ดูเนื้อที่ที่ Docker ใช้
- docker rm [Container ID] = ลบ Containers
- docker rmi [ชื่อimage] = ลบ Dockerimage
- docker volume  Inspect = ตรวจสอบใน Volume
- docker volume rm [ชื่อvolume] = ลบ Volume
- docker-compose up -d = Run Container ด้วย docker-compose
- docker-compose down = หยุดการทำงานของ Container 
- docker exec -it = Remote ไปยัง sh shell
- docker network create [ชื่อที่จะตั้ง] = สร้าง Bridge network 
- docker network rm [ชื่อnetwork] = ลบ Bridge network
