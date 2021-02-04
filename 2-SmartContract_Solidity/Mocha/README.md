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

<p>
let car;

beforeEach(() => {
    car = new Car();
})
</p>

<p>
describe('Car', () => { <br>
    it('can park', () => {
        assert.equal(car.park(), 'stopped');
    });

    it('can drive', () => {
        assert.equal(car.drive(), 'vroom');
    })
})
</p>
