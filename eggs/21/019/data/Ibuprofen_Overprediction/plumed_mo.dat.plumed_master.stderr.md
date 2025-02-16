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
[fv-az1112-175:66895] *** Process received signal ***
[fv-az1112-175:66895] Signal: Aborted (6)
[fv-az1112-175:66895] Signal code:  (-6)
[fv-az1112-175:66895] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd8e1045330]
[fv-az1112-175:66895] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd8e109eb2c]
[fv-az1112-175:66895] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd8e104527e]
[fv-az1112-175:66895] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8e10288ff]
[fv-az1112-175:66895] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8e14a5ff5]
[fv-az1112-175:66895] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8e14bb0da]
[fv-az1112-175:66895] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8e14a5a55]
[fv-az1112-175:66895] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8e14a5a6f]
[fv-az1112-175:66895] [ 8] plumed_master(+0x146dd)[0x557ec765b6dd]
[fv-az1112-175:66895] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd8e102a1ca]
[fv-az1112-175:66895] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd8e102a28b]
[fv-az1112-175:66895] [11] plumed_master(+0x15365)[0x557ec765c365]
[fv-az1112-175:66895] *** End of error message ***
</pre>
{% endraw %}
