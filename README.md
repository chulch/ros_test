# ros_test
my first code repo
hello

---

## 2023-02-13

---

* first
  * turtlebot3
  * VMware 16 Ubuntu 20.04
* second
```shell

git clone https://github.com/chulch/ros_test.git
cat README.md
ros2 run turtlesim turtlesim_node --ros-args --remap _node:=my_turtle
ros2 node list
git config --global user.email "--------@-----.com"
git config --global user.name "chulch"
ros2 topic list

```



## 2023_2_14

* 노드 만들기
```shell
ros2 pkg create --build-type ament_python my package
ros2 run my_package mp
ros2 topic echo /messagepub
```
* 노드등록, 노드에서 토픽보내기
