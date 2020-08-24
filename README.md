<!-- ### Hi there 👋 -->

<!--
**muath-ye/muath-ye** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
**Languages and Tools:**  

<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/ccc16358ac4530c6a69b1b80c7223cd2744dea83/topics/php/php.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/laravel/laravel.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bootstrap/bootstrap.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/jquery/jquery.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/arduino/arduino.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/android/android.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/wordpress/wordpress.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/windows/windows.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/linux/linux.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/ubuntu/ubuntu.png"></code>
<code><img height="20" src="https://repository-images.githubusercontent.com/31792824/fb7e5700-6ccc-11e9-83fe-f602e1e1a9f1"></code>

<!--- if you have forked this to use on your profile, Change the `github-readme-stats.anuraghazra1.vercel.app` to `github-readme-stats.vercel.app` --->

<!-- ![Muath's github stats](https://github-readme-stats.vercel.app/api?username=muath-ye&show_icons=true&theme=radical) -->

[![Social banner for jh3y](https://github.com/muath-ye/muath-ye/raw/master/Developer activity-amico-min.png)](https://twitter.com/muathye)
<h1 align='center'> Hi! :wave:</h1>
<p align='center'>
I'm Muath.
</p>
<p align='center'>For enquiries, mail me muathye@gmail.com or over on <a href="https://twitter.com/muathye">Twitter</a>.</p>

<h1 align='center'><i>Stay awesome! and take a look at my resume</i></h1>

```php
<?php
/**
 * Muath Ahmed Assawadi
 * +967777643646
 * muathye@gmail.com
 * https://github/muath-ye
 */
namespace Muath;

use Muath\ScientialQualifications;
use Muath\Courses;
use Muath\Experiences;
use Muath\Skills;
use Muath\SpeakingLanguages;

class Resume
{
    // Sciential Qualifications
    public function scientialQualifications()
    {
        $qualifications = array();
        
        $qualifications[] = ScientialQualifications::BachelorDegree([
            "Degree Name"       => "Information Technology & Computer Science",
            "Qualifier Name"    => "Sana'a University - Information Technology & Computer Science",
            "Date"              => "April, 2014 - June, 2018",
            "Qualifier Address" => "Sana'a - Yemen",
        ]);

        $qualifications[] = ScientialQualifications::SecondarySchool([
            "Degree Name"       => "Sciential Section General Secondary School",
            "Qualifier Name"    => "Al-Kuwait Secondary School",
            "Date"              => "March, 2009 - May, 2012",
            "Qualifier Address" => "Sana'a - Yemen",
        ]);

        return $qualifications;
    }
    
    // Courses
    public function courses()
    {
        $courses = array();
        
        $courses[] = Courses::englishDiploma([
            "Degree Name"       => "Intermediate English Diploma",
            "Qualifier Name"    => "Canadian Training Center",
            "Date"              => "April, 2012 - August, 2012",
            "Qualifier Address" => "Sana'a - Yemen",
        ]);

        $courses[] = Courses::accounting([
            "Degree Name"       => "Accounting for Non-accountant Diploma",
            "Qualifier Name"    => "Ministry of Adult and Sport",
            "Date"              => "Feb, 2013 - March, 2013",
            "Qualifier Address" => "Sana'a - Yemen",
        ]);

        $courses[] = Courses::graphics([
            "Degree Name"       => "Graphics (PhotoShop - Illustrator - InDesign) Diploma",
            "Qualifier Name"    => "Ministry of Adult and Sport",
            "Date"              => "March, 2014 - May, 2014",
            "Qualifier Address" => "Sana'a - Yemen",
        ]);

        $courses[] = Courses::montage([
            "Degree Name"       => "Montage (Premier - AfterEffect) Diploma",
            "Qualifier Name"    => "Ministry of Adult and Sport",
            "Date"              => "August, 2016 - September, 2016",
            "Qualifier Address" => "Sana'a - Yemen",
        ]);

        $courses[] = "And more courses, events and associations from April, 2011 till now.";

        return $courses;
    }

    // Experiences
    public function experiences()
    {
        $experiences = array();
        
        $experiences[] = Experiences::infiniteCloud([
            "Company Name"    => "InfiniteCloud",
            "Company Website" => "https://infinitecloud.co",
            "Date"            => "December, 2018 - now",
            "Company Address" => "Sana'a - Yemen",
        ]);

        return $experiences;
    }

    // Skills
    public function skills()
    {
        $skills = array();
        
        $skills[] = Skills::someSkills([
            "PHP Language",
            "Laravel Framework",
            "Api Development",
            "JavaScript Language",
            "VueJs Framework",
            "Bootstrap Library",
            "Jquery Library",
            "Git VCS",
            "Github",
            "WordPress",
            "Windows Server",
            "Hosting Administration" => [
                "Shared",
                "VPS",
                "Dedicated",
            ],
            "Adobe" => [
                "XD",
                "PhotoShop",
                "Illustrator",
                "InDesign",
                "Premier",
                "After Effect",
            ],
            "MS Office"
        ]);

        return $skills;
    }

    // Speaking Languages
    public function speakingLanguages()
    {
        $languages = array();
        
        $languages[] = SpeakingLanguages::languages([
            "Arabic"  => "Native Language",
            "English" => "Well Experienced",
            "Germany" => "Beginner",
        ]);

        return $languages;
    }
}
```
