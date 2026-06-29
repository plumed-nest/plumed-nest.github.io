**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w21-s5.628/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:11157] *** Process received signal ***
[runnervmmklqx:11157] Signal: Aborted (6)
[runnervmmklqx:11157] Signal code:  (-6)
[runnervmmklqx:11157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f27c1045330]
[runnervmmklqx:11157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f27c109eb2c]
[runnervmmklqx:11157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f27c104527e]
[runnervmmklqx:11157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f27c10288ff]
[runnervmmklqx:11157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f27c14a5ff5]
[runnervmmklqx:11157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f27c14bb0da]
[runnervmmklqx:11157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f27c14a5a55]
[runnervmmklqx:11157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f27c14a5a6f]
[runnervmmklqx:11157] [ 8] plumed(+0x146dd)[0x55ccd454c6dd]
[runnervmmklqx:11157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f27c102a1ca]
[runnervmmklqx:11157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f27c102a28b]
[runnervmmklqx:11157] [11] plumed(+0x15365)[0x55ccd454d365]
[runnervmmklqx:11157] *** End of error message ***
</pre>
{% endraw %}
