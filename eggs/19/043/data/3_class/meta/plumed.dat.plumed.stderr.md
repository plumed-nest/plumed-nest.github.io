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
[runnervmkj6or:12259] *** Process received signal ***
[runnervmkj6or:12259] Signal: Aborted (6)
[runnervmkj6or:12259] Signal code:  (-6)
[runnervmkj6or:12259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe421845330]
[runnervmkj6or:12259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe42189eb2c]
[runnervmkj6or:12259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe42184527e]
[runnervmkj6or:12259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4218288ff]
[runnervmkj6or:12259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe421ca5ff5]
[runnervmkj6or:12259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe421cbb0da]
[runnervmkj6or:12259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe421ca5a55]
[runnervmkj6or:12259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe421ca5a6f]
[runnervmkj6or:12259] [ 8] plumed(+0x146dd)[0x557d2a3906dd]
[runnervmkj6or:12259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe42182a1ca]
[runnervmkj6or:12259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe42182a28b]
[runnervmkj6or:12259] [11] plumed(+0x15365)[0x557d2a391365]
[runnervmkj6or:12259] *** End of error message ***
</pre>
{% endraw %}
