SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/dut.v
VERILOG_SOURCES += $(PWD)/tests/wrapper.v

MODULE = dut_test
TOPLEVEL = dut_test

include $(shell cocotb-config 
--makefiles)/Makefile.sim
