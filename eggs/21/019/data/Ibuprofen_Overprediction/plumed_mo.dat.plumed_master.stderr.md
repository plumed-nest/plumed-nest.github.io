**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmw9dnm:13035] *** Process received signal ***
[runnervmw9dnm:13035] Signal: Aborted (6)
[runnervmw9dnm:13035] Signal code:  (-6)
[runnervmw9dnm:13035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c66a45330]
[runnervmw9dnm:13035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c66a9eb2c]
[runnervmw9dnm:13035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c66a4527e]
[runnervmw9dnm:13035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c66a288ff]
[runnervmw9dnm:13035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c66ea5ff5]
[runnervmw9dnm:13035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c66ebb0da]
[runnervmw9dnm:13035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c66ea5a55]
[runnervmw9dnm:13035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c66ea5a6f]
[runnervmw9dnm:13035] [ 8] plumed_master(+0x146dd)[0x55cc784846dd]
[runnervmw9dnm:13035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c66a2a1ca]
[runnervmw9dnm:13035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c66a2a28b]
[runnervmw9dnm:13035] [11] plumed_master(+0x15365)[0x55cc78485365]
[runnervmw9dnm:13035] *** End of error message ***
</pre>
{% endraw %}
