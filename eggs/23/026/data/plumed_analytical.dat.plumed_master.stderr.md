**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_analytical.dat   
Download: [zipped raw stdout](plumed_analytical.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analytical.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[pkrvm7jw40e0xgp:06655] *** Process received signal ***
[pkrvm7jw40e0xgp:06655] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06655] Signal code:  (-6)
[pkrvm7jw40e0xgp:06655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c43645330]
[pkrvm7jw40e0xgp:06655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c4369eb2c]
[pkrvm7jw40e0xgp:06655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c4364527e]
[pkrvm7jw40e0xgp:06655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c436288ff]
[pkrvm7jw40e0xgp:06655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c43aa5ff5]
[pkrvm7jw40e0xgp:06655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c43abb0da]
[pkrvm7jw40e0xgp:06655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c43aa5a55]
[pkrvm7jw40e0xgp:06655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c43aa5a6f]
[pkrvm7jw40e0xgp:06655] [ 8] plumed_master(+0x146dd)[0x55ca4aaa26dd]
[pkrvm7jw40e0xgp:06655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c4362a1ca]
[pkrvm7jw40e0xgp:06655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c4362a28b]
[pkrvm7jw40e0xgp:06655] [11] plumed_master(+0x15365)[0x55ca4aaa3365]
[pkrvm7jw40e0xgp:06655] *** End of error message ***
</pre>
{% endraw %}
