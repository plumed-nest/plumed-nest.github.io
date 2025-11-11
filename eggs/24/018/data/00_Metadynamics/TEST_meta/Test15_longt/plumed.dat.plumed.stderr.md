**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:07087] *** Process received signal ***
[runnervmw9dnm:07087] Signal: Aborted (6)
[runnervmw9dnm:07087] Signal code:  (-6)
[runnervmw9dnm:07087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f44ab245330]
[runnervmw9dnm:07087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f44ab29eb2c]
[runnervmw9dnm:07087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f44ab24527e]
[runnervmw9dnm:07087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44ab2288ff]
[runnervmw9dnm:07087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44ab6a5ff5]
[runnervmw9dnm:07087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44ab6bb0da]
[runnervmw9dnm:07087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44ab6a5a55]
[runnervmw9dnm:07087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44ab6a5a6f]
[runnervmw9dnm:07087] [ 8] plumed(+0x146dd)[0x557f59abb6dd]
[runnervmw9dnm:07087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f44ab22a1ca]
[runnervmw9dnm:07087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f44ab22a28b]
[runnervmw9dnm:07087] [11] plumed(+0x15365)[0x557f59abc365]
[runnervmw9dnm:07087] *** End of error message ***
</pre>
{% endraw %}
