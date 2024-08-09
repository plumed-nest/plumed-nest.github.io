**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az693-738:06647] *** Process received signal ***
[fv-az693-738:06647] Signal: Aborted (6)
[fv-az693-738:06647] Signal code:  (-6)
[fv-az693-738:06647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f21cfc42520]
[fv-az693-738:06647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f21cfc969fc]
[fv-az693-738:06647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f21cfc42476]
[fv-az693-738:06647] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f21cfc287f3]
[fv-az693-738:06647] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f21d00a2b9e]
[fv-az693-738:06647] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f21d00ae20c]
[fv-az693-738:06647] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f21d00ae277]
[fv-az693-738:06647] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f21d00ae52b]
[fv-az693-738:06647] [ 8] plumed_master(+0x14274)[0x560705246274]
[fv-az693-738:06647] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f21cfc29d90]
[fv-az693-738:06647] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f21cfc29e40]
[fv-az693-738:06647] [11] plumed_master(+0x14ed5)[0x560705246ed5]
[fv-az693-738:06647] *** End of error message ***
</pre>
{% endraw %}
