<img src ="https://github.com/neelbavarva/Ethereum/blob/main/2-SmartContract_Solidity/Mocha/Images/1.png">

<p>
class Car{
    park(){
        return 'stopped';
    }

    drive(){
        return 'vroom';
    }
}
</p0>

<p>
let car;

beforeEach(() => {
    car = new Car();
})
</p>

<p>
describe('Car', () => {
    it('can park', () => {
        assert.equal(car.park(), 'stopped');
    });

    it('can drive', () => {
        assert.equal(car.drive(), 'vroom');
    })
})
</p>
