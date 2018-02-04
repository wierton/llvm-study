set(LLVM_LINK_COMPONENTS
  Core
  ExecutionEngine
  MC
  MCJIT
  Option
  Support
  native
  )

add_clang_executable(mytest
  main.cpp
  )
