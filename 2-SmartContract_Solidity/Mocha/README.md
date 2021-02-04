<img src ="https://github.com/neelbavarva/Ethereum/blob/main/2-SmartContract_Solidity/Mocha/Images/1.png">

<p>
class Car{<br>
    park(){<br>
        return 'stopped';<br>
    }<br>
    <br>
    drive(){<br>
        return 'vroom';<br>
    }<br>
}<br>
</p>
<br>
<p>
let car;<br>
<br>
beforeEach(() => {<br>
    car = new Car();<br>
})<br>
</p>
<br>
<p>
describe('Car', () => { <br>
    it('can park', () => {<br>
        assert.equal(car.park(), 'stopped');<br>
    });<br>
<br>
    it('can drive', () => {<br>
        assert.equal(car.drive(), 'vroom');<br>
    })<br>
})<br>
</p>
