The User is used inside the MainNavigation and can display an avatar and username. It can be also used inside forms, etc. with the extended prop.

```js
import { User } from '@wfp/ui';
```

```js
<User
  alt="Image Alt text"
  ellipsis={false}
  name="Max Mustermann"
  image="https//www.example.com/image.jpg"
/>
```

### Extended User

```js
<User
  alt="Image Alt text"
  description={
    <List kind="simple" small>
      <ListItem>Business Support Assistant G4</ListItem>
      <ListItem>Fixed Term</ListItem>
    </List>
  }
  extendedDescription={
    <List kind="simple" small>
      <ListItem title="First level supervisor">Marie Curie</ListItem>
      <ListItem title="Mrc">Tanzania Country Office</ListItem>
      <ListItem title="Head of unit">Max Planck</ListItem>
    </List>
  }
  name="Albert Einstein"
  image="https//www.example.com/image.jpg"
/>
```