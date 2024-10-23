**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[fv-az585-767:11368] *** Process received signal ***
[fv-az585-767:11368] Signal: Aborted (6)
[fv-az585-767:11368] Signal code:  (-6)
[fv-az585-767:11368] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0518442520]
[fv-az585-767:11368] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f05184969fc]
[fv-az585-767:11368] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0518442476]
[fv-az585-767:11368] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f05184287f3]
[fv-az585-767:11368] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f05188a2b9e]
[fv-az585-767:11368] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f05188ae20c]
[fv-az585-767:11368] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f05188ae277]
[fv-az585-767:11368] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f05188ae52b]
[fv-az585-767:11368] [ 8] plumed_master(+0x14254)[0x556ca4b15254]
[fv-az585-767:11368] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0518429d90]
[fv-az585-767:11368] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0518429e40]
[fv-az585-767:11368] [11] plumed_master(+0x14eb5)[0x556ca4b15eb5]
[fv-az585-767:11368] *** End of error message ***
</pre>
{% endraw %}
