# hook 钩子：

        import { useState } from 'react';

        function Example() {
            const [count, setCoount] = useState(1);
        }
        return (
           <div>
             <p>你点击了{count}次</p>
             <button onClick={() => setCount(count + 1)}>点击</button>
           </div>
        )
