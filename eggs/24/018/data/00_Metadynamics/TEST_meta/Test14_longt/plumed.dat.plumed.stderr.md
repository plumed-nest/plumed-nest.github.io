**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:05984] *** Process received signal ***
[runnervmmklqx:05984] Signal: Aborted (6)
[runnervmmklqx:05984] Signal code:  (-6)
[runnervmmklqx:05984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6145645330]
[runnervmmklqx:05984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f614569eb2c]
[runnervmmklqx:05984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f614564527e]
[runnervmmklqx:05984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61456288ff]
[runnervmmklqx:05984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6145aa5ff5]
[runnervmmklqx:05984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6145abb0da]
[runnervmmklqx:05984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6145aa5a55]
[runnervmmklqx:05984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6145aa5a6f]
[runnervmmklqx:05984] [ 8] plumed(+0x146dd)[0x55f4f2efb6dd]
[runnervmmklqx:05984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f614562a1ca]
[runnervmmklqx:05984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f614562a28b]
[runnervmmklqx:05984] [11] plumed(+0x15365)[0x55f4f2efc365]
[runnervmmklqx:05984] *** End of error message ***
</pre>
{% endraw %}
