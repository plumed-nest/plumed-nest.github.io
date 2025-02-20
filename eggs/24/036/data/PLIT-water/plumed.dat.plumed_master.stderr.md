**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az816-356:05635] *** Process received signal ***
[fv-az816-356:05635] Signal: Aborted (6)
[fv-az816-356:05635] Signal code:  (-6)
[fv-az816-356:05635] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5e1845330]
[fv-az816-356:05635] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5e189eb2c]
[fv-az816-356:05635] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5e184527e]
[fv-az816-356:05635] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5e18288ff]
[fv-az816-356:05635] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5e1ca5ff5]
[fv-az816-356:05635] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5e1cbb0da]
[fv-az816-356:05635] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5e1ca5a55]
[fv-az816-356:05635] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5e1ca5a6f]
[fv-az816-356:05635] [ 8] plumed_master(+0x146dd)[0x5608d4e5e6dd]
[fv-az816-356:05635] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5e182a1ca]
[fv-az816-356:05635] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5e182a28b]
[fv-az816-356:05635] [11] plumed_master(+0x15365)[0x5608d4e5f365]
[fv-az816-356:05635] *** End of error message ***
</pre>
{% endraw %}
