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
[runnervmkj6or:07681] *** Process received signal ***
[runnervmkj6or:07681] Signal: Aborted (6)
[runnervmkj6or:07681] Signal code:  (-6)
[runnervmkj6or:07681] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb823045330]
[runnervmkj6or:07681] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb82309eb2c]
[runnervmkj6or:07681] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb82304527e]
[runnervmkj6or:07681] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8230288ff]
[runnervmkj6or:07681] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8234a5ff5]
[runnervmkj6or:07681] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8234bb0da]
[runnervmkj6or:07681] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8234a5a55]
[runnervmkj6or:07681] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8234a5a6f]
[runnervmkj6or:07681] [ 8] plumed_master(+0x146dd)[0x5649c43376dd]
[runnervmkj6or:07681] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb82302a1ca]
[runnervmkj6or:07681] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb82302a28b]
[runnervmkj6or:07681] [11] plumed_master(+0x15365)[0x5649c4338365]
[runnervmkj6or:07681] *** End of error message ***
</pre>
{% endraw %}
