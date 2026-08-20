SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v 
VERILOG_SOURCES += $(PWD)/wrappers/wrapper.v
or:
rm -rf sim_build
$(Make) sim MODULE=dut_test TOPLEVEL=dut_test
include $(shell cocotb-config --makefiles)/Makefile.sim
