**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/lig_in_qm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az1046-619:05690] *** Process received signal ***
[fv-az1046-619:05690] Signal: Aborted (6)
[fv-az1046-619:05690] Signal code:  (-6)
[fv-az1046-619:05690] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b75245330]
[fv-az1046-619:05690] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b7529eb2c]
[fv-az1046-619:05690] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b7524527e]
[fv-az1046-619:05690] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b752288ff]
[fv-az1046-619:05690] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b756a5ff5]
[fv-az1046-619:05690] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b756bb0da]
[fv-az1046-619:05690] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b756a5a55]
[fv-az1046-619:05690] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b756a5a6f]
[fv-az1046-619:05690] [ 8] plumed(+0x146dd)[0x55be45b436dd]
[fv-az1046-619:05690] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b7522a1ca]
[fv-az1046-619:05690] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b7522a28b]
[fv-az1046-619:05690] [11] plumed(+0x15365)[0x55be45b44365]
[fv-az1046-619:05690] *** End of error message ***
</pre>
{% endraw %}
