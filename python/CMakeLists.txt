include(GrPython)

if(NOT PYTHONINTERP_FOUND)
  return()
endif()

GR_PYTHON_INSTALL(
  FILES __init__.py doppler.py
  DESTINATION ${GR_PYTHON_DIR}/gpredict
)
