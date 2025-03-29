**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAMe_G6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[fv-az789-879:68412] *** Process received signal ***
[fv-az789-879:68412] Signal: Aborted (6)
[fv-az789-879:68412] Signal code:  (-6)
[fv-az789-879:68412] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f239c045330]
[fv-az789-879:68412] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f239c09eb2c]
[fv-az789-879:68412] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f239c04527e]
[fv-az789-879:68412] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f239c0288ff]
[fv-az789-879:68412] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f239c4a5ff5]
[fv-az789-879:68412] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f239c4bb0da]
[fv-az789-879:68412] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f239c4a5a55]
[fv-az789-879:68412] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f239c4a5a6f]
[fv-az789-879:68412] [ 8] plumed(+0x146dd)[0x55a9f78c96dd]
[fv-az789-879:68412] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f239c02a1ca]
[fv-az789-879:68412] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f239c02a28b]
[fv-az789-879:68412] [11] plumed(+0x15365)[0x55a9f78ca365]
[fv-az789-879:68412] *** End of error message ***
</pre>
{% endraw %}
