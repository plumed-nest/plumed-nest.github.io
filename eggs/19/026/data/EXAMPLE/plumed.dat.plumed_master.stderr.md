**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[pkrvmf6wy0o8zjz:42724] *** Process received signal ***
[pkrvmf6wy0o8zjz:42724] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:42724] Signal code:  (-6)
[pkrvmf6wy0o8zjz:42724] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6b1fa45330]
[pkrvmf6wy0o8zjz:42724] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6b1fa9eb2c]
[pkrvmf6wy0o8zjz:42724] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6b1fa4527e]
[pkrvmf6wy0o8zjz:42724] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6b1fa288ff]
[pkrvmf6wy0o8zjz:42724] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6b1fea5ff5]
[pkrvmf6wy0o8zjz:42724] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6b1febb0da]
[pkrvmf6wy0o8zjz:42724] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6b1fea5a55]
[pkrvmf6wy0o8zjz:42724] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6b1fea5a6f]
[pkrvmf6wy0o8zjz:42724] [ 8] plumed_master(+0x146dd)[0x559c28a746dd]
[pkrvmf6wy0o8zjz:42724] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6b1fa2a1ca]
[pkrvmf6wy0o8zjz:42724] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6b1fa2a28b]
[pkrvmf6wy0o8zjz:42724] [11] plumed_master(+0x15365)[0x559c28a75365]
[pkrvmf6wy0o8zjz:42724] *** End of error message ***
</pre>
{% endraw %}
