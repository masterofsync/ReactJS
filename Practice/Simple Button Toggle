class ButtonOnOff extends React.Component{
  constructor(props){
    super(props);
    this.state={isTurnedOn: true};
    this.triggerButton=this.triggerButton.bind(this);
  }
  
  triggerButton(){
    this.setState(prevState=>({
      isTurnedOn:!prevState.isTurnedOn
    }));
  }
  
  render(){
    return(
    <button onClick={this.triggerButton}>
      {this.state.isTurnedOn ? 'ON' : 'OFF'}    
    </button>
    );
  }
}

ReactDOM.render(
<ButtonOnOff />,
  document.getElementById('root')
)