**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmgx7h7:09117] *** Process received signal ***
[runnervmgx7h7:09117] Signal: Aborted (6)
[runnervmgx7h7:09117] Signal code:  (-6)
[runnervmgx7h7:09117] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa6f6e45330]
[runnervmgx7h7:09117] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa6f6e9ec0c]
[runnervmgx7h7:09117] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa6f6e4527e]
[runnervmgx7h7:09117] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa6f6e288ff]
[runnervmgx7h7:09117] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa6f72a5ff5]
[runnervmgx7h7:09117] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa6f72bb0da]
[runnervmgx7h7:09117] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa6f72a5a55]
[runnervmgx7h7:09117] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa6f72a5a6f]
[runnervmgx7h7:09117] [ 8] plumed(+0x146dd)[0x559dfd52f6dd]
[runnervmgx7h7:09117] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa6f6e2a1ca]
[runnervmgx7h7:09117] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa6f6e2a28b]
[runnervmgx7h7:09117] [11] plumed(+0x15365)[0x559dfd530365]
[runnervmgx7h7:09117] *** End of error message ***
</pre>
{% endraw %}
