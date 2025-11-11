**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmw9dnm:06076] *** Process received signal ***
[runnervmw9dnm:06076] Signal: Aborted (6)
[runnervmw9dnm:06076] Signal code:  (-6)
[runnervmw9dnm:06076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd99a445330]
[runnervmw9dnm:06076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd99a49eb2c]
[runnervmw9dnm:06076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd99a44527e]
[runnervmw9dnm:06076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd99a4288ff]
[runnervmw9dnm:06076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd99a8a5ff5]
[runnervmw9dnm:06076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd99a8bb0da]
[runnervmw9dnm:06076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd99a8a5a55]
[runnervmw9dnm:06076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd99a8a5a6f]
[runnervmw9dnm:06076] [ 8] plumed_master(+0x146dd)[0x55f8ebd356dd]
[runnervmw9dnm:06076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd99a42a1ca]
[runnervmw9dnm:06076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd99a42a28b]
[runnervmw9dnm:06076] [11] plumed_master(+0x15365)[0x55f8ebd36365]
[runnervmw9dnm:06076] *** End of error message ***
</pre>
{% endraw %}
