# RaduRusu1.github.io

some random notes including how to use MarkDig in C#
>> TBD Prokjectname, either MarkDownPad or WinTreePad, depending what I want to emphasise, and if still available

[MD cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
        

````using Markdig;
````using Markdig.Extensions;

````                var s = textBox1.Text;
````                var html = Markdown.ToHtml(s);
````                string path = @"c:\radu\temp\t.html";
````                File.WriteAllText(path, html);
````                webBrowser1.Navigate(path);


