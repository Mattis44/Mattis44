<h1 id="header" align="center"> <strong> Mattis </strong> </h1>
<br/>

<div id="header" align="center">
  <img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" width="100"/>
  
  
  <div id="badges">
  <a href="https://www.linkedin.com/in/mattis-naud-692836226/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
  
  
  
  ---
  
  ### :milky_way: About me
  
  </div>
  
  ```jsx
    
    const Mattis = async (props) => {  
        const [name, setName] = useState("Mattis")
        const [location, setLocation] = useState('')

        const ageRef = useRef(null)

        const student = props.student || false;        
        const discord = "mattis."

        useEffect(() => {
          const getLoc = () => {
            axios.get('/api/location')
                .then((res) => setLocation(res.data?.location ?? "Nantes"))
          }
        getLoc()
        }, [])

        return (
        <input type=text ref={ageRef} value='21'/>
      )
    }

```
  
  <div align='center'>
  
  ---


### Languages :

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="Typescript" alt="Typescript" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg" title="C++" alt="C++" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/rust/rust-original.svg" title="Rust" alt="Rust" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  
  
  
  
</div>
  
  ### Tools : 
  
  <div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" title="Express" alt="Express" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="40" height="40"/>
    
    
  

  </div>
  
  ---

### Stats :
  
  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Mattis44&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)
  
</div>

