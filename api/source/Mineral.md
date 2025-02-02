# Mineral

A mineral deposit. Can be harvested by creeps with a `WORK` body part using the extractor structure. 
Learn more about minerals from [this article](/resources.html).

<table class="table gameplay-info">
    <tbody>
    <tr>
        <td><strong>Regeneration amount</strong></td>
        <td><code>DENSITY_LOW</code>: 15,000 <br /> <code>DENSITY_MODERATE</code>: 35,000<br /> <code>DENSITY_HIGH</code>: 70,000 <br /> <code>DENSITY_ULTRA</code>: 100,000</td>
    </tr>
    <tr>
        <td><strong>Regeneration time</strong></td>
        <td>50,000 ticks</td>
    </tr>
    <tr>
        <td><strong>Density change probability</strong></td>
        <td><code>DENSITY_LOW</code>: 100% chance <br /> <code>DENSITY_MODERATE</code>: 5% chance<br /> <code>DENSITY_HIGH</code>: 5% chance <br /> <code>DENSITY_ULTRA</code>: 100% chance</td>
    </tr>
    </tbody>
</table>

{% page inherited/RoomObject.md %} 

{% api_property density 'number' %}



The density that this mineral deposit will be refilled to once <code>ticksToRegeneration</code> reaches 0. This is one of the <code>DENSITY_*</code> constants.



{% api_property mineralAmount 'number' %}



The remaining amount of resources.



{% api_property mineralType 'string' %}



The resource type, <code>RESOURCE_*</code>常量之一。



{% api_property id 'string' %}



一个唯一的对象标识。你可以使用<a href="#Game.getObjectById"><code>Game.getObjectById</code></a>方法获取对象实例。



{% api_property ticksToRegeneration 'number' %}



The remaining time after which the deposit will be refilled.


