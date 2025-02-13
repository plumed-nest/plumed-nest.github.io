**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az1046-619:05760] *** Process received signal ***
[fv-az1046-619:05760] Signal: Aborted (6)
[fv-az1046-619:05760] Signal code:  (-6)
[fv-az1046-619:05760] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5efe45330]
[fv-az1046-619:05760] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5efe9eb2c]
[fv-az1046-619:05760] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5efe4527e]
[fv-az1046-619:05760] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5efe288ff]
[fv-az1046-619:05760] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5f02a5ff5]
[fv-az1046-619:05760] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5f02bb0da]
[fv-az1046-619:05760] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5f02a5a55]
[fv-az1046-619:05760] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5f02a5a6f]
[fv-az1046-619:05760] [ 8] plumed_master(+0x146dd)[0x55d7ee09a6dd]
[fv-az1046-619:05760] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5efe2a1ca]
[fv-az1046-619:05760] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5efe2a28b]
[fv-az1046-619:05760] [11] plumed_master(+0x15365)[0x55d7ee09b365]
[fv-az1046-619:05760] *** End of error message ***
</pre>
{% endraw %}
