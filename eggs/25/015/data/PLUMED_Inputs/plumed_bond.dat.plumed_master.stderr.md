**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmvrwv9:04623] *** Process received signal ***
[runnervmvrwv9:04623] Signal: Aborted (6)
[runnervmvrwv9:04623] Signal code:  (-6)
[runnervmvrwv9:04623] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff7a5845330]
[runnervmvrwv9:04623] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff7a589eb2c]
[runnervmvrwv9:04623] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff7a584527e]
[runnervmvrwv9:04623] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7a58288ff]
[runnervmvrwv9:04623] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7a5ca5ff5]
[runnervmvrwv9:04623] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7a5cbb0da]
[runnervmvrwv9:04623] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7a5ca5a55]
[runnervmvrwv9:04623] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7a5ca5a6f]
[runnervmvrwv9:04623] [ 8] plumed_master(+0x146dd)[0x55725c79e6dd]
[runnervmvrwv9:04623] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff7a582a1ca]
[runnervmvrwv9:04623] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff7a582a28b]
[runnervmvrwv9:04623] [11] plumed_master(+0x15365)[0x55725c79f365]
[runnervmvrwv9:04623] *** End of error message ***
</pre>
{% endraw %}
