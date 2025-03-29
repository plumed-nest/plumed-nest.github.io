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
[fv-az789-879:66672] *** Process received signal ***
[fv-az789-879:66672] Signal: Aborted (6)
[fv-az789-879:66672] Signal code:  (-6)
[fv-az789-879:66672] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3f85645330]
[fv-az789-879:66672] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3f8569eb2c]
[fv-az789-879:66672] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3f8564527e]
[fv-az789-879:66672] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3f856288ff]
[fv-az789-879:66672] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3f85aa5ff5]
[fv-az789-879:66672] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3f85abb0da]
[fv-az789-879:66672] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3f85aa5a55]
[fv-az789-879:66672] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3f85aa5a6f]
[fv-az789-879:66672] [ 8] plumed_master(+0x146dd)[0x55bb0c1526dd]
[fv-az789-879:66672] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3f8562a1ca]
[fv-az789-879:66672] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3f8562a28b]
[fv-az789-879:66672] [11] plumed_master(+0x15365)[0x55bb0c153365]
[fv-az789-879:66672] *** End of error message ***
</pre>
{% endraw %}
