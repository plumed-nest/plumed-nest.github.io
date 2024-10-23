**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DUMPGRID with label @117 : keyword ARG is compulsory for this action
[fv-az801-114:06471] *** Process received signal ***
[fv-az801-114:06471] Signal: Aborted (6)
[fv-az801-114:06471] Signal code:  (-6)
[fv-az801-114:06471] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9be9042520]
[fv-az801-114:06471] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9be90969fc]
[fv-az801-114:06471] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9be9042476]
[fv-az801-114:06471] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9be90287f3]
[fv-az801-114:06471] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9be94a2b9e]
[fv-az801-114:06471] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9be94ae20c]
[fv-az801-114:06471] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9be94ae277]
[fv-az801-114:06471] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9be94ae52b]
[fv-az801-114:06471] [ 8] plumed_master(+0x14254)[0x560e19430254]
[fv-az801-114:06471] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9be9029d90]
[fv-az801-114:06471] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9be9029e40]
[fv-az801-114:06471] [11] plumed_master(+0x14eb5)[0x560e19430eb5]
[fv-az801-114:06471] *** End of error message ***
</pre>
{% endraw %}
