**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmw9dnm:11833] *** Process received signal ***
[runnervmw9dnm:11833] Signal: Aborted (6)
[runnervmw9dnm:11833] Signal code:  (-6)
[runnervmw9dnm:11833] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f286ce45330]
[runnervmw9dnm:11833] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f286ce9eb2c]
[runnervmw9dnm:11833] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f286ce4527e]
[runnervmw9dnm:11833] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f286ce288ff]
[runnervmw9dnm:11833] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f286d2a5ff5]
[runnervmw9dnm:11833] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f286d2bb0da]
[runnervmw9dnm:11833] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f286d2a5a55]
[runnervmw9dnm:11833] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f286d2a5a6f]
[runnervmw9dnm:11833] [ 8] plumed(+0x146dd)[0x55dd095be6dd]
[runnervmw9dnm:11833] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f286ce2a1ca]
[runnervmw9dnm:11833] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f286ce2a28b]
[runnervmw9dnm:11833] [11] plumed(+0x15365)[0x55dd095bf365]
[runnervmw9dnm:11833] *** End of error message ***
</pre>
{% endraw %}
