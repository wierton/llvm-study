set(LLVM_LINK_COMPONENTS
  Core
  ExecutionEngine
  MC
  MCJIT
  Option
  Support
  native
  )

add_llvm_tool(interpreter
  main.cpp
  )

