**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az1440-40:61799] *** Process received signal ***
[fv-az1440-40:61799] Signal: Aborted (6)
[fv-az1440-40:61799] Signal code:  (-6)
[fv-az1440-40:61799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f93cea45330]
[fv-az1440-40:61799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f93cea9eb2c]
[fv-az1440-40:61799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f93cea4527e]
[fv-az1440-40:61799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93cea288ff]
[fv-az1440-40:61799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93ceea5ff5]
[fv-az1440-40:61799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93ceebb0da]
[fv-az1440-40:61799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93ceea5a55]
[fv-az1440-40:61799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93ceea5a6f]
[fv-az1440-40:61799] [ 8] plumed_master(+0x146dd)[0x5612a9ae86dd]
[fv-az1440-40:61799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f93cea2a1ca]
[fv-az1440-40:61799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f93cea2a28b]
[fv-az1440-40:61799] [11] plumed_master(+0x15365)[0x5612a9ae9365]
[fv-az1440-40:61799] *** End of error message ***
</pre>
{% endraw %}
