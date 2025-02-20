**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/lig_in_qm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az1374-933:06097] *** Process received signal ***
[fv-az1374-933:06097] Signal: Aborted (6)
[fv-az1374-933:06097] Signal code:  (-6)
[fv-az1374-933:06097] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd5f045330]
[fv-az1374-933:06097] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd5f09eb2c]
[fv-az1374-933:06097] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd5f04527e]
[fv-az1374-933:06097] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd5f0288ff]
[fv-az1374-933:06097] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd5f4a5ff5]
[fv-az1374-933:06097] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd5f4bb0da]
[fv-az1374-933:06097] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd5f4a5a55]
[fv-az1374-933:06097] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd5f4a5a6f]
[fv-az1374-933:06097] [ 8] plumed_master(+0x146dd)[0x555ac319d6dd]
[fv-az1374-933:06097] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd5f02a1ca]
[fv-az1374-933:06097] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd5f02a28b]
[fv-az1374-933:06097] [11] plumed_master(+0x15365)[0x555ac319e365]
[fv-az1374-933:06097] *** End of error message ***
</pre>
{% endraw %}
