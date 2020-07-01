# ReactHooks

Creating react app
  npx create-react-app
  
React Hooks
  1.useState()
  2.useEffect()
  3.useRef()
  4.useCallback()
  
 1.useState()
  const [count, setCount] = useState(0)
  const [color, setColor] = useState(null)
  
 2.useEffect()
  useEffect(()=>{
    setColor(randomColor)
  }, [])
