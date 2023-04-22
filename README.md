<picture>
  <img align='right' src="https://streak-stats.demolab.com?user=Anoerak&theme=dark&mode=weekly" height="150"/>
</picture>
<img align='left' src="https://media.giphy.com/media/D2j3xOKq0O0qQ8BOVC/giphy.gif" width="150">

<br><br><br><br>

<h2>
  Hi,
  I'm Sebastien! 
</h2>

<br><br>

![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)
![forthebadge](https://forthebadge.com/images/badges/built-with-grammas-recipe.svg)
![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)
![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)

<img align='right' src="https://media.giphy.com/media/8m4gPv1UFz1jmiCtKd/giphy.gif" width="180">


<br>


<p>
  <em>
    Student at <a href="https://openclassrooms.com/">OpenClassrooms</a><img src="https://media.giphy.com/media/XuBtcsV266vepmoEYG/giphy.gif" width="50">
    <br>
    Web Developer at <a href="https://iamseb.dev">IamSeb.dev</a><img src="https://media.giphy.com/media/iIGT8Y1rOYhBpdHh1C/giphy.gif" width="50">
  </em>
</p>


<br><br><br><br>


<picture>
  <img align='left' src="https://github-readme-stats.vercel.app/api?username=Anoerak&count_private=true&show_icons=true&theme=radical" />
</picture>
<picture>
  <img align='right' src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anoerak&layout=compact&langs_count=8"/>
</picture>


<br><br><br><br><br><br><br><br><br><br>


### <img src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" width="50"> A little more about me...  

````javascript
class Anørak {
	constructor() {
		this._pronouns = 'he' | 'his';
		this._languages = ['HTML5', 'Twig', 'CSS3', 'SCSS', 'JavaScript', 'PHP', 'MySQL'];
		this._frameworks = ['React.JS', 'Vue.JS', 'Solid.JS', 'Symfony'];
		this._librairies = ['Redux', 'Bootstrap', 'Bulma', 'Chart.JS'];
		this._workInProgress = 'Nailing the unit test with PHPUnit!!';
		this._story = [];
	}

	set story(data) {
		this._story = data;
	}

	get story() {
		return this._story;
	}
}
````


<br><br>


### <img src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" width="50"> A little more about my story...

````javascript
const me = new Anørak();

const story = [
	{
		previous_experiences: {
			'2002-2016': 'A long carrier into logistics and sales for several french fret companies such as STG, STEF or MADRIAS.',
			'2016 - 2018': '2 years as a yoga teacher based in St Louis, MO, USA',
			'2018 - 2022': '4 years as France sales manager for a veterinarian laboratory',
			'2021': 'In parallel with my job at the time as a national sales manager, I started a program with OpenClassrooms in order 
			to get an official certifiation as a web developer (HTML, CSS, Node, MySQL, Vue). Done in 4 months instead of 6 as 
			planned by OpenClassrooms.',
			'2022': 'I quit my job and start another training with OpenClassrooms in order to get a certification as an advanced JS & 
			React web application developer. I managed to validate all the projects in about 5 and 1/2 months instead of 12 and 
			use the extra time to do all the projects of the PHP & Symfony Web Developer program (a total different 12 months program). 
			Today, I\'m about to officially follow the PHP & Symfony program and use the extra time to study others languages, frameworks, 
			librairies and get a job!!!',
		},
	},
];

me.story = story;
````


<br><br>


### <img src="https://media.giphy.com/media/eNAsjO55tPbgaor7ma/giphy.gif" width="50"> A little more about what I'm studying at the moment... 

````jsx
const subjectsActuallyStudied = () => {
  const {data, loading, isError, errorMessage} = useFetch('./anørak.json');
  const subjects = data;
  const error = errorMessage;
  
  return (
    <div className="main">
      <div className="home_content">
        {isError ? (
          <div className="error">
            Something went wrong : <br /> {error && error}
          </div>
        ) : loading ? (
          <Loader />
        ) : (
          <div className="cards">
            {listOfSubjects.map((place) => (
		// You got it, I try to get better with React, Next and Solid JS
              <Link to={`/details/${subject.id}`} key={subject.id}>
                <Card id={subject.id} name={subject.title} picture={subject.emote} />
              </Link>
            ))}
          </div>
        )}
      </div>
    </div>
  );
}
````


<br><br>


### <img src="https://media.giphy.com/media/JqDcpPX8vWahUny0pE/giphy.gif" width="50"> A little more about what I aim for...  

````php
<?php

namespace App\Anørak;

use App\Entity\Story;

class Me implements Goals
{
  private $story;
  
  public function __construct()
  {
    $this->story = new Story;
  }
  
  public function communicateAboutMyStory(): object
  {
    return $this->story;
  }
  
  public function getAJob(): array
  {
    return [
      'workplace' => [
        'company' => 'Maybe yours!!!',
        'position' => 'Let\'s talk about it',
        'salary' => 'The right amount for the right position'
      ],
	  'location' => [
	  	'Worldwide' => 'Anywhere as long as we can work fully remotely',
		'Stockholm' => 'Hybrid if remote 3 to 4 days a week, otherwise full remote',
		'Montreal or Quebec' => 'Hybrid if remote 3 to 4 days a week, otherwise full remote'
	  ]
    ];
  }
  
  public function enjoyMyfamily(): array
  {
    return [
      'What I mean' => 'As a father since october 2022, I intend to see my son growing up and spend as much time as I can with 
       him and his mother. COVID-19 taught us that we don\'t need to spend hours commuting, gathering in offices to do the exact 
       same thing we can do from home.',
      'What it means' => 'As mentioned in the desired locations for my future job, I\'ll consider a position only if we can work 
       remotely.'
    ];
  }

  public function practiceHobbies(): array
  {
    return [
      'Yoga' => 'Since 2012, I practice at least 3 times a week and teach AcroYoga every Tuesday evening.',
      'Hiking' => 'Once a week, we go for a hike. We long for something different every week if possible and really look forward for this family time.'
      'Video Games' => 'I\'ve been playing videos games since my parents brought back home our first Amstrad 6128+... Yup, I\'m that old :). Since then, I\'ve been playing mostly on console but I\'ve switched to 
       PC in 2021 and enjoy it a lot. I play all sort of games but at the moment, I play a lot of DayZ, The Last of Us and Hunt:Showdown.'
    ];
  }
}
````


<br><br>


## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=Anoerak&theme=nord&column=7)](https://github.com/Anoerak/github-profile-trophy)


<br><br>


## 🗂️ Highlight Projects

<a href="https://github.com/Anoerak/SnowTricks">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=Anoerak&repo=SnowTricks&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="SnowTricks" />
</a>

<a href="https://github.com/Anoerak/Proust_Sebastien_P12_23092022">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=Anoerak&repo=Proust_Sebastien_P12_23092022&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="Proust_Sebastien_P12_23092022" />
</a>

<a href="https://github.com/Anoerak/Proust_Sebastien_P6_13072022">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=Anoerak&repo=Proust_Sebastien_P6_13072022&show_icons=true&line_height=27&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=22272e" alt="Proust_Sebastien_P6_13072022" />
</a>
