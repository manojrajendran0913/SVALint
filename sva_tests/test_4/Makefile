
run: 
	vlib work
	vlog -sv -mfcu  test_4.sv test_4_tb.sv -l comp_log.log
	vsim -c tb_property -do "run -all;exit" -l run_log.log
