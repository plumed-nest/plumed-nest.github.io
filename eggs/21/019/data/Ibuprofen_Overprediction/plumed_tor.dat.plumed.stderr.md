**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ATOMS141=9314,9319,9310,9313
Maybe a missing space or a typo?
[fv-az1272-851:09368] *** Process received signal ***
[fv-az1272-851:09368] Signal: Aborted (6)
[fv-az1272-851:09368] Signal code:  (-6)
[fv-az1272-851:09368] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f479f242520]
[fv-az1272-851:09368] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f479f2969fc]
[fv-az1272-851:09368] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f479f242476]
[fv-az1272-851:09368] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f479f2287f3]
[fv-az1272-851:09368] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f479f6a2b9e]
[fv-az1272-851:09368] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f479f6ae20c]
[fv-az1272-851:09368] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f479f6ae277]
[fv-az1272-851:09368] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f479f6ae52b]
[fv-az1272-851:09368] [ 8] plumed(+0x12f48)[0x56150c690f48]
[fv-az1272-851:09368] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f479f229d90]
[fv-az1272-851:09368] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f479f229e40]
[fv-az1272-851:09368] [11] plumed(+0x131e5)[0x56150c6911e5]
[fv-az1272-851:09368] *** End of error message ***
</pre>
{% endraw %}
