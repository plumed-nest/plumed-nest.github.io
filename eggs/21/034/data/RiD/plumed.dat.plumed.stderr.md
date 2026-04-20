**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmeorf1:08494] *** Process received signal ***
[runnervmeorf1:08494] Signal: Aborted (6)
[runnervmeorf1:08494] Signal code:  (-6)
[runnervmeorf1:08494] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67e7a45330]
[runnervmeorf1:08494] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67e7a9eb2c]
[runnervmeorf1:08494] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67e7a4527e]
[runnervmeorf1:08494] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67e7a288ff]
[runnervmeorf1:08494] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67e7ea5ff5]
[runnervmeorf1:08494] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67e7ebb0da]
[runnervmeorf1:08494] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67e7ea5a55]
[runnervmeorf1:08494] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67e7ea5a6f]
[runnervmeorf1:08494] [ 8] plumed(+0x146dd)[0x560aca0146dd]
[runnervmeorf1:08494] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67e7a2a1ca]
[runnervmeorf1:08494] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67e7a2a28b]
[runnervmeorf1:08494] [11] plumed(+0x15365)[0x560aca015365]
[runnervmeorf1:08494] *** End of error message ***
</pre>
{% endraw %}
