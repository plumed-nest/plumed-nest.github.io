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
[fv-az1983-395:65012] *** Process received signal ***
[fv-az1983-395:65012] Signal: Aborted (6)
[fv-az1983-395:65012] Signal code:  (-6)
[fv-az1983-395:65012] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d92645330]
[fv-az1983-395:65012] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d9269eb2c]
[fv-az1983-395:65012] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d9264527e]
[fv-az1983-395:65012] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d926288ff]
[fv-az1983-395:65012] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d92aa5ff5]
[fv-az1983-395:65012] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d92abb0da]
[fv-az1983-395:65012] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d92aa5a55]
[fv-az1983-395:65012] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d92aa5a6f]
[fv-az1983-395:65012] [ 8] plumed_master(+0x146dd)[0x55ac5fa0d6dd]
[fv-az1983-395:65012] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d9262a1ca]
[fv-az1983-395:65012] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d9262a28b]
[fv-az1983-395:65012] [11] plumed_master(+0x15365)[0x55ac5fa0e365]
[fv-az1983-395:65012] *** End of error message ***
</pre>
{% endraw %}
