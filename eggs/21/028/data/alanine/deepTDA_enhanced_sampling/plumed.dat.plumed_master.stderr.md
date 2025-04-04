**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  alanine/deepTDA_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::add_buffer_to<std::bad_alloc>'
what():  std::bad_alloc
[fv-az805-507:08006] *** Process received signal ***
[fv-az805-507:08006] Signal: Aborted (6)
[fv-az805-507:08006] Signal code:  (-6)
[fv-az805-507:08006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6aba045330]
[fv-az805-507:08006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6aba09eb2c]
[fv-az805-507:08006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6aba04527e]
[fv-az805-507:08006] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6aba0288ff]
[fv-az805-507:08006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6aba4a5ff5]
[fv-az805-507:08006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6aba4bb0da]
[fv-az805-507:08006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6aba4a5a55]
[fv-az805-507:08006] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6aba4a5a6f]
[fv-az805-507:08006] [ 8] plumed_master(+0x146dd)[0x56143db646dd]
[fv-az805-507:08006] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6aba02a1ca]
[fv-az805-507:08006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6aba02a28b]
[fv-az805-507:08006] [11] plumed_master(+0x15365)[0x56143db65365]
[fv-az805-507:08006] *** End of error message ***
</pre>
{% endraw %}
