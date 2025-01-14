<!--
 * @Date: 2025-01-14 23:54:10
 * @LastEditors: Future Meng
 * @LastEditTime: 2025-01-14 23:55:56
-->

docker build ./

docker login --username=b*****@163.com registry.cn-beijing.aliyuncs.com

docker images

docker tag [ImageId] registry.cn-beijing.aliyuncs.com/futuremeng/ragflow:latest

docker push registry.cn-beijing.aliyuncs.com/futuremeng/ragflow:latest