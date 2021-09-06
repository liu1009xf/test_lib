add_executable(bar bar.cpp)

target_link_libraries(bar PRIVATE TestLib::testlib)

install(
  TARGETS bar
  RUNTIME DESTINATION bin
)
