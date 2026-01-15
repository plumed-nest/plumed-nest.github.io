**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervmi13qx:33990] *** Process received signal ***
[runnervmi13qx:33990] Signal: Aborted (6)
[runnervmi13qx:33990] Signal code:  (-6)
[runnervmi13qx:33990] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f278da45330]
[runnervmi13qx:33990] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f278da9eb2c]
[runnervmi13qx:33990] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f278da4527e]
[runnervmi13qx:33990] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f278da288ff]
[runnervmi13qx:33990] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f278dea5ff5]
[runnervmi13qx:33990] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f278debb0da]
[runnervmi13qx:33990] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f278dea5a55]
[runnervmi13qx:33990] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f278dea5a6f]
[runnervmi13qx:33990] [ 8] plumed_master(+0x146dd)[0x55db032386dd]
[runnervmi13qx:33990] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f278da2a1ca]
[runnervmi13qx:33990] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f278da2a28b]
[runnervmi13qx:33990] [11] plumed_master(+0x15365)[0x55db03239365]
[runnervmi13qx:33990] *** End of error message ***
</pre>
{% endraw %}
