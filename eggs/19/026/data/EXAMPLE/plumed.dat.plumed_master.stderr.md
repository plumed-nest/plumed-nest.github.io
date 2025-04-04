**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az2207-973:13773] *** Process received signal ***
[fv-az2207-973:13773] Signal: Aborted (6)
[fv-az2207-973:13773] Signal code:  (-6)
[fv-az2207-973:13773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f066ac45330]
[fv-az2207-973:13773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f066ac9eb2c]
[fv-az2207-973:13773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f066ac4527e]
[fv-az2207-973:13773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f066ac288ff]
[fv-az2207-973:13773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f066b0a5ff5]
[fv-az2207-973:13773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f066b0bb0da]
[fv-az2207-973:13773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f066b0a5a55]
[fv-az2207-973:13773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f066b0a5a6f]
[fv-az2207-973:13773] [ 8] plumed_master(+0x146dd)[0x55d6f4b166dd]
[fv-az2207-973:13773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f066ac2a1ca]
[fv-az2207-973:13773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f066ac2a28b]
[fv-az2207-973:13773] [11] plumed_master(+0x15365)[0x55d6f4b17365]
[fv-az2207-973:13773] *** End of error message ***
</pre>
{% endraw %}
