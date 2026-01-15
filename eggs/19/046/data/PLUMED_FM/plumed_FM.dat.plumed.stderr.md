**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[runnervmmtnos:36887] *** Process received signal ***
[runnervmmtnos:36887] Signal: Aborted (6)
[runnervmmtnos:36887] Signal code:  (-6)
[runnervmmtnos:36887] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffbcd045330]
[runnervmmtnos:36887] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffbcd09eb2c]
[runnervmmtnos:36887] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffbcd04527e]
[runnervmmtnos:36887] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffbcd0288ff]
[runnervmmtnos:36887] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffbcd4a5ff5]
[runnervmmtnos:36887] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffbcd4bb0da]
[runnervmmtnos:36887] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffbcd4a5a55]
[runnervmmtnos:36887] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffbcd4a5a6f]
[runnervmmtnos:36887] [ 8] plumed(+0x146dd)[0x5640b61406dd]
[runnervmmtnos:36887] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffbcd02a1ca]
[runnervmmtnos:36887] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffbcd02a28b]
[runnervmmtnos:36887] [11] plumed(+0x15365)[0x5640b6141365]
[runnervmmtnos:36887] *** End of error message ***
</pre>
{% endraw %}
