# http://ros.org/doc/groovy/api/catkin/html/user_guide/supposed.html
cmake_minimum_required(VERSION 2.8.3)
project(prace_gripper_driver)

find_package(catkin REQUIRED )

catkin_package(
    DEPENDS  # TODO
    CATKIN_DEPENDS # TODO
    INCLUDE_DIRS # TODO include
    LIBRARIES # TODO
)

install(DIRECTORY ros/
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/ros
)