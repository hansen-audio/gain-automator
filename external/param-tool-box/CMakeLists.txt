cmake_minimum_required(VERSION 3.15.0)

include(FetchContent)

FetchContent_Declare(
    param-tool-box
    GIT_REPOSITORY ${HA_GIT_REPOSITORY_URL}/hansen-audio/param-tool-box.git
    GIT_TAG origin/master
)

FetchContent_MakeAvailable(param-tool-box)