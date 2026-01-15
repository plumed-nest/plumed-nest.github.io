**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmmtnos:39953] *** Process received signal ***
[runnervmmtnos:39953] Signal: Aborted (6)
[runnervmmtnos:39953] Signal code:  (-6)
[runnervmmtnos:39953] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7f8445330]
[runnervmmtnos:39953] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7f849eb2c]
[runnervmmtnos:39953] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7f844527e]
[runnervmmtnos:39953] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7f84288ff]
[runnervmmtnos:39953] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7f88a5ff5]
[runnervmmtnos:39953] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7f88bb0da]
[runnervmmtnos:39953] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7f88a5a55]
[runnervmmtnos:39953] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7f88a5a6f]
[runnervmmtnos:39953] [ 8] plumed(+0x146dd)[0x55a2774966dd]
[runnervmmtnos:39953] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7f842a1ca]
[runnervmmtnos:39953] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7f842a28b]
[runnervmmtnos:39953] [11] plumed(+0x15365)[0x55a277497365]
[runnervmmtnos:39953] *** End of error message ***
</pre>
{% endraw %}
