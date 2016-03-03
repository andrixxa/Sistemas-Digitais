module test_on_off;

	reg clock;

	always #2 clock = ~clock;

  	initial begin
    	$dumpvars(0,clock);
    	clock <= 1;
    	#20;
    	$finish;
	end

endmodule
