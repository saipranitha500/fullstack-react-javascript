# fullstack-react-javascript
import './App.css';

const Hello = (props) => {
  return (
    <div>
      <p>Hello {props.name}</p>
    </div>
  )
}
function App() {
  const now = new Date()
  const a = 10
  const b = 20

  return (
    <div>
      <p>Hello world, it is {now.toString()}</p>
      <p>
        {a} plus {b} is {a + b}
      </p>
      <Hello name="Maya" />
      <Hello name="Pekka" />
    </div>
  );
}


export default App;

O/P:
Hello world, it is Sat Jun 05 2021 14:51:32 GMT+0530 (India Standard Time)

10 plus 20 is 30

Hello Maya

Hello Pekka
