# aux_source_directory(. SRC_LIST)
set(SRC_LIST
    myrpcapplication.cc
    myrpcconfig.cc
    rpcheader.pb.cc
    myrpcprovider.cc
    myrpcchannel.cc
    myrpccontroller.cc
    logger.cc
    zookeeperutil.cc)
add_library(myrpc ${SRC_LIST})
target_link_libraries(myrpc mymuduo pthread zookeeper_mt)