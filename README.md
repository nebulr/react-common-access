# React Singleton Access

Import accessor for whatever you want to put in it!

```
import Singleton from 'react-singleton-access'
import Components from './components';
import Styles from './styles';
import Constants from './constants';

Singleton.Components = Components;
Singleton.Styles = Styles;
Singleton.Constants = Constants;

...

import { Components, Styles, Constants } from 'react-singleton-access';

...

```