## Copyright 2019 Andrey Stepanov (standmit)
##
## This program is free software: you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation, either version 3 of the License.
##
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with this program.  If not, see <https://www.gnu.org/licenses/>.

cmake_minimum_required(VERSION 2.8.3)
project(vagrant_simulation)

find_package(catkin REQUIRED)

catkin_package()

install(
	DIRECTORY launch rviz
	DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)