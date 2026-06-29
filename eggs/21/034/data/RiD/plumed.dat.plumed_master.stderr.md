**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmmklqx:09566] *** Process received signal ***
[runnervmmklqx:09566] Signal: Aborted (6)
[runnervmmklqx:09566] Signal code:  (-6)
[runnervmmklqx:09566] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bdd445330]
[runnervmmklqx:09566] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bdd49eb2c]
[runnervmmklqx:09566] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bdd44527e]
[runnervmmklqx:09566] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bdd4288ff]
[runnervmmklqx:09566] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bdd8a5ff5]
[runnervmmklqx:09566] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bdd8bb0da]
[runnervmmklqx:09566] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bdd8a5a55]
[runnervmmklqx:09566] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bdd8a5a6f]
[runnervmmklqx:09566] [ 8] plumed_master(+0x146dd)[0x559f755f46dd]
[runnervmmklqx:09566] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bdd42a1ca]
[runnervmmklqx:09566] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bdd42a28b]
[runnervmmklqx:09566] [11] plumed_master(+0x15365)[0x559f755f5365]
[runnervmmklqx:09566] *** End of error message ***
</pre>
{% endraw %}
