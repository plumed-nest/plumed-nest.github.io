**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_bond.dat   
Download: [zipped raw stdout](plumed_bond.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_bond.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "MOLECULES" is not known.
[runnervmi13qx:32932] *** Process received signal ***
[runnervmi13qx:32932] Signal: Aborted (6)
[runnervmi13qx:32932] Signal code:  (-6)
[runnervmi13qx:32932] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9fb2845330]
[runnervmi13qx:32932] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9fb289eb2c]
[runnervmi13qx:32932] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9fb284527e]
[runnervmi13qx:32932] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9fb28288ff]
[runnervmi13qx:32932] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9fb2ca5ff5]
[runnervmi13qx:32932] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9fb2cbb0da]
[runnervmi13qx:32932] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9fb2ca5a55]
[runnervmi13qx:32932] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9fb2ca5a6f]
[runnervmi13qx:32932] [ 8] plumed(+0x146dd)[0x55cfa77076dd]
[runnervmi13qx:32932] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9fb282a1ca]
[runnervmi13qx:32932] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9fb282a28b]
[runnervmi13qx:32932] [11] plumed(+0x15365)[0x55cfa7708365]
[runnervmi13qx:32932] *** End of error message ***
</pre>
{% endraw %}
